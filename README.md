# Ruby Bug: Unexpected Behavior with instance_variable_set and Assignment

This repository demonstrates an uncommon bug in Ruby related to the interaction between `instance_variable_set` and direct assignment within a method.  The example shows that modifying an instance variable using `instance_variable_set` doesn't reflect changes made through direct assignment within a getter method.