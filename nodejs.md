## Node.js Coding Standards

#### GitHub
1. Create commit per one logical change to your branch

2. Please label each commit messages with followings (http://udacity.github.io/git-styleguide/)
FEAT: new feature
FIX: bugfix
REFACTOR: code refactoring (no functional change)
STYLE: formatting the code (no functional change)
DOCS: changes to documentation (no functional change)
CHORE: updating configurations & build tasks & etc (no production code change)


## Coding Style Guidelines

#### Naming convention

1. Use camelCasing for function names (eg. function myFunc)
(https://en.wikipedia.org/wiki/Naming_convention_(programming) javascript section)
2. Use under_scores for variable names (eg. var my_var)
3. Use CamelCasing with first letter capital for class names (eg. class MyFunc), but treat instances of classes as variables

#### Spaces and Braces

1. Curly braces after all functions should be seperated by space, and should start on the same line.

```javascript
function() {
  //code
}
```
instead of

```javascript
function(){
  //code
}

or

function()
{
  //code
}
```

2. Length of every line should not exceed 80 characters. seperate code into different line
```javascript
{
  "status": "abcd",
  "result": null
};
```

instead of
```javascript
{
  "status": "abcd",  "result": null
};
```

3. All tabs must be in a length of 2, and consisted of tabs, not spaces.


#### Et Cetera

1. Enclose any string expression with double quotes, instead of single quotes
