# (*) Printing the Response in Other Formats

Replace `"/graphql"` from the URL to output the data in a different format: XML or as properties, or any custom one (implementation takes very few lines of code).

```less
// Output as XML: Replace /graphql with /xml
/api/xml/?query={posts{id title author{id name}}}

// Output as props: Replace /graphql with /props
/api/props/?query={posts{id title excerpt}}
```

<a href="https://newapi.getpop.org/api/xml/?query={posts{id title author{id name}}}">View query results #1</a>

<a href="https://newapi.getpop.org/api/props/?query={posts{id title excerpt}}">View query results #2</a>

## XML

TODO

## Props/CSV

TODO
