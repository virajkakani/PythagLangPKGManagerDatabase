# Deps.txt spec

* Make sure your deps.txt has the links to your dependencies
* Separate all links with commas
* Put all links in quotes

## Examples:
Lets say the deps.txt in your lib is as follows:
  ```
  "https://github.com/example/math",
  (other deps go here)
```

And the dependencies of math are as follows:
  ```
  "https://github.com/example/ex1",
  "https://github.com/example/ex2",
  "https://github.com/example/ex3"
```

Then your deps.txt should be:
```
  "https://github.com/example/math",
  "https://github.com/example/ex1",
  "https://github.com/example/ex2",
  "https://github.com/example/ex3"
  ...
```
(it must inlude all files in math)
