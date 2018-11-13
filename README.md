# gatsby-source-cat-facts

```
yarn add gatsby-source-cat-facts
```

Want Cat Facts ([source](https://alexwohlbruck.github.io/cat-facts/)) in your Gatsby app? Yes, obviously we all do.

Install this package, and add `'gatsby-source-cat-facts'` to your plugins array in `gatsby-config.js`. Run `gatsby develop`, head to the GraphiQL IDE and run:

```
{
   allCatFacts {
    catFacts: edges {
      catFact: node {
        text
      }
    }
  }
}
```

Look! Cat Facts!

🐈
