# oneness

## Tutorial: https://www.youtube.com/watch?v=n1mdAPFq2Os  


##  Documentation of the process:  
- Server is set using ApolloServer  
- MongoDB connected using Atlas
- created models(Post, User) and tested the DB connection with Gql
- created graphql to separate all the queries from the index.js file
- jwt and bcrypt installed
- graphql/resolvers/users.js user registeration and password encryption 
- added a code to resolvers-users to prevent username duplicates on registeration
- added validation for signup and login
- added getPosts and getPost by id to resolvers and typeDefs
- added create post functionality
- added delete post functionality (mutation in resolvers -> posts.js)
- *working on comments* creating comments is added but needs work **this will be updated**
