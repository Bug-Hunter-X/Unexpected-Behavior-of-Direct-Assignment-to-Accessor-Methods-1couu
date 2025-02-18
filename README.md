# Unexpected Behavior of Direct Assignment to Accessor Methods in Ruby

This repository demonstrates an uncommon error in Ruby where directly assigning a value to an accessor method does not update the underlying instance variable.

The `bug.rb` file shows the problem: attempting to change the value using `my_object.value = 30` doesn't change the instance variable `@value`.  The solution (`bugSolution.rb`) illustrates the correct approach using the setter method or `instance_variable_set`.