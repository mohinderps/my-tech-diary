### March 9th, 2020

1. Took a short and quick tutorial on Markdown from [this site](www.markdowntutorial.com).

### March 10th, 2020

1. Created my first npm package and published it on npm registry. Here is the [link](https://www.npmjs.com/package/super-basic-math-utils).
2. Create a scoped npm package and published it on npm registry. Here is the [link](https://www.npmjs.com/package/@mohindersaluja/basic-math-utils).
3. Created a scenario in which a package depends on itself. A -> A( -> A -> A -> ....). npm install did not break down in this case. Instead  it install the same package in the node_modules but just one level deep. So no infinite loop occurs.