## What is this?

这是Graphql学习过程的Demo库，使用apollo server

see: https://www.apollographql.com/docs/apollo-server/


## Test
```graphql endpoint doc
{
  books {
    title
    author
  }
}
```

```graphql endpoint doc
mutation addBook($title: String, $author: String) {
  addBook(title: $title, author: $author) {
    author
    title
  }
}

{
  "title": "best book",
  "author": "yixing"
}
```
## Note

## Problem

