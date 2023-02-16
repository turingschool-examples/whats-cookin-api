# whats-cookin-api

This repo was created to be used with the whats cookin project.

## Set Up

Clone this down, and `cd` into it.  Then run:

`npm install`

`npm start`

## Endpoints

| Description | URL | Method | Required Properties for Request | Sample Successful Response |
| --- | --- | --- | --- | --- |
| Get all users | http://localhost:3001/api/v1/users | GET | none | An array containing all users |
| Get all ingredients | http://localhost:3001/api/v1/ingredients | GET | none | An array containing all ingredients |
| Get all recipes | http://localhost:3001/api/v1/recipes | GET | none | An array containing all recipes |
| Add recipe to cook for a user | http://localhost:3001/api/v1/usersRecipes | POST | { userID: `<number>`, recipeID: `<number>` } | {message: "Recipe # `<recipeID>` was added for User # `<userID>`" } |
