# How-to
- Install Node.js and npm to handle packages and dependancies
- Run "npm install" to install all dependancies
- Currently it is running wihtout bcrypt but there are some pages which break due to certain expectations from the methods removed.

### Features:
* Frontpage
* Subreddits
* Submitting comments / posts / links
* Voting on posts / comments
* Saving posts / comments
* Editing posts / comments
* Deleting posts / comments
* Subscribing
* Searching
* Sorting
* Profile pages
* Karma system
* Relative time
* Validation
* Change password / delete account
* API

# API:
URL | Method | Details | Body
---- | ---- | ---- | ----
/api/frontpage | GET | Retrieves all posts from frontpage
/api/r/```subreddit``` | GET | Retrieves all posts from ```subreddit```
/api/post/```id``` | GET | Retrieves post by ```id```
/api/post/```id```/comments | GET | Retrieves all comments for post by ```id```
/api/u/```user``` | GET | Retrieves profile information about ```user```
/api/u/```user```/posts | GET | Retrieves all posts by ```user```
/api/u/```user```/comments | GET | Retrieves all comments by ```user```
/api/register | POST | Registers an account | ```username```, ```password```