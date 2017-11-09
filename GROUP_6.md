# GROUP 6

* Marguerite, Zach, Daniel, Maria

### GOAL

* create a book club app using the gutenburg e-books library (public dataset)
search gutenberg library
users would create a profile,
	review books read
	make reccomendations
	and comment on other users posts

### Database structure

* create a bookClub_db
Users table
	id (primary key)
	name
	age
	gender
	body
	date joined
Reccommendations Table
	id (primary key)
	book title
	body
	timestamp
	user (foriegn key)
Reviews Table
	id (primary key)
	book title
	body
	timestamp
	user (foreign key)
Comments Table
 [{
		user
		timestamp
		body
	}]

### Folder structure

* config
	config.json 

* models (anything that reacts with the database)
	index.js 
	recommend.js
	review.js
	user.js
	book.js

* views (any front-end things)
	user.handlebars
	review.handlebars
	recommendation.handlebars
	index.handlebars
	--Layouts
		main.handlebars
		profile.handlebars
		book.handlebarsl

(controller is anything else)
* routes
	api-routes.js
	html-routes.js 
package.json
server.js




* Basic Frontend (index.html)
* download database
make sure we can access it

filter and exclude based on language