> Engineered a database and RESTful API with CRUD operations allowing users to access data about the latest movies, theaters, and reviews.

### Tasks
- Build an API following RESTful principles
- Provided access to relevant information through route and query parameters
- Utilizie middleware packages
- Created an error handler for the case where a route doesn't exist
- Customize knexfile file for staging
- Used Knex to write database queries
- Complete CRUD routes in an Express server
- Utilized nested and joined data with Knex (treeize)
- Used Knex's migration tool to write database migrations
- Deployed to Vercel

### Routes
- /reviews [PUT/DELETE]
- /theaters
- /movies
- - /movies?is_showing=true
- - /movies/:movieId
- - /movies/:movieId/theaters
- - /movies/:movieId/reviews
