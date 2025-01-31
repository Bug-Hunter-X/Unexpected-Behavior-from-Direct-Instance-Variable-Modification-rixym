# Ruby Bug: Unexpected Behavior from Direct Instance Variable Modification

This repository demonstrates a common, yet subtle bug in Ruby that arises from directly modifying instance variables outside of defined methods.  Directly manipulating instance variables using `instance_variable_set` or `instance_variable_get` can bypass method logic and lead to unpredictable results, especially in larger or more complex applications.

The `bug.rb` file contains code exhibiting this issue. The `bugSolution.rb` file offers a more robust and maintainable solution.

## Reproducing the Bug

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `ruby bug.rb`.