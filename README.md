# GraphQL

https://velog.io/@gwak2837/GraphQL


## Query
// localhost:4000
query {
  movies {
    name
  }
}


## Mutation
// localhost:4000
mutation {
  addMovie(name:"인셉션", rating: 8) {
    name
  }
}