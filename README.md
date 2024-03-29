# RSS-aggregator

## description 
* Created a user-friendly RSS feed aggregator that delivers curated content from various sources directly to users' devices, ensuring seamless access to personalized updates in a concise and efficient manner.

#  Instructions

* clone project `git clone https://github.com/Moemen-Gaballah/RSS-aggregator.git`
* open dir `cd RSS-aggregator`
* edit file ".env" to update `DB_URL` 
* to migrate database `cd sql/schema && goose postgres postgres://postgres:postgres@localhost:5432/rssagg up`
* run project `cd ../../ && go build && ./RSS.exe`
* now project running `http://127.0.0.1:8080/`
* import postman collection from root dir

### Done

- [x] Express Server running on `http://localhost:8080/`
- [x] Migrations
- [x] add credentials to `.env` file
- [x] generate API key instead of JWT (add to Headers Authorization: ApiKey token)
- [x] Middleware
- [x] Store User
- [x] Get User
- [x] Store Feed
- [x] Get Feeds
- [x] Store Feed follows
- [x] Delete Feed follows
- [x] scraper to get feeds and store it in table posts
- [x] get posts depend on user login



### TODO

- [] refactor add more folder MVC.
- [] login by email and password then return token
- [] write unit test.
- **_and more._**..
