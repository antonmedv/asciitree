# Draw ASCII tree

```
npm install asciitree
```

## Usage

```js
var draw_tree = require('./asciitree');

var tree = ['root', 'child 1', ['child 2', 'node']];

console.log(draw_tree(tree));

```

Result:

```
      root___
     /       \
  child 1  child 2
              |
            node
```

## Examples

```
        1___
       /    \
      2      3
     / \    / \
    4   5  6   7
   / \        / \
  8   9      10 11
```

```
      SELECT_________________
     /            \          \
    .___         FROM       JOIN
   /    \          |       /    \
  a  city_name  people  address ON
                                 |
                                 =___________
                                /            \
                               .____          .
                              /     \        / \
                              p  address_id  a  id
```

```
     div_______________________________________________________________________________
    /   \                      \    \                      \    \                      \
  text  div_________________  text  div_________________  text  div_________________  text
       /   \    \     \     \      /   \    \     \     \      /   \    \     \     \
     text   i  text  span  text  text   i  text  span  text  text   i  text  span  text
                       |                           |                           |
                     text                        text                        text
```
