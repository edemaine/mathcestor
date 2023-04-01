# mathcestor: Render an HTML ancestor tree from [Mathematics Genealogy Project](https://www.mathgenealogy.org/)

Given the ID of a mathematician from the
[Mathematics Genealogy Project](https://www.mathgenealogy.org/),
this script walks up the tree of academic ancestors
(advisors, advisors' advisors, etc.),
and builds an HTML rendering of that tree.

## [Example](https://erikdemaine.org/family/#ancestors)

For example, [here is the rendered tree of academic ancestors of
the author of this software](https://erikdemaine.org/family/#ancestors).

## Usage

After [installing Node](https://nodejs.org/en/download/),
you can install (or update) this tool via

```sh
npm install -g mathcestor@latest
```

Then you can use the script as follows:

```sh
mathcestor ID >out.html
```

where `ID` is the number at the end of a URL from
https://www.mathgenealogy.org/
