A basic implementation of an Apollo GraphQL server

Start the server
> npm start

To use:
Open in your browser
localhost:4001/graphiql

In the left panel, enter the text below and run
query {
  books {
    title
    author
  }
}