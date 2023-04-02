# mathcestor: Ancestor/descendant tree from [Mathematics Genealogy Project](https://www.mathgenealogy.org/), rendered to HTML

Given the ID of a mathematician from the
[Mathematics Genealogy Project](https://www.mathgenealogy.org/),
this script walks up the tree of academic ancestors
(advisors, advisors' advisors, etc.) or
down the tree of academic descendants (students, students' students, etc.),
and builds an HTML rendering of that tree.

## Examples

For example, here are the rendered trees for the author of this software:
* [Academic ancestors](https://erikdemaine.org/family/#ancestors)
* [Academic descendants](https://erikdemaine.org/family/#descendants)

## Usage

After [installing Node](https://nodejs.org/en/download/),
you can install (or update) this tool via

```sh
npm install -g mathcestor@latest
```

Then you can use the script as follows:

```sh
mathcestor ID >individual.html
mathcestor ID advisors >ancestors.html
mathcestor ID students >descendants.html
```

where `ID` is the number at the end of a URL from
https://www.mathgenealogy.org/
