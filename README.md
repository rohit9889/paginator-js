# paginator-js

A very simple and clean implementation for using the pagination feature in any project.

# Usage

Suppose, you have an array of objects that you need to paginate.

```
let array = [
  {a: 1},
  {a: 2},
  {a: 3},
  ...
  ...
  ...
  {a: 100}
]
```

Now if you need to get the third page with 10 items you can use the code below

```
array.paginate(3, 10)
```