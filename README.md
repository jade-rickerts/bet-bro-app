#Development TIMELINE

#1.	Initial Setup

##Pages
* Add Landing Page
* Add Bets Page that lists all the bets
##Bet Model
* Description
* Image
* Date
###Example
[
	{description: “Germany vs Albania”, image: “http://www.bet-bro.com”, date: “23/06/17”},
	{description: “Brazil vs Argentina”, image: “http://www.bet-bro.com”, date: “24/06/17”},
	{description: “France vs England”, image: “http://www.bet-bro.com”, date: “27/06/17”},
]

#2.	Layout and Style
* Create Header and Footer
* Add Bootstrap

#3.	Creating New Bet (Admin)
* Setup new bet POST route
* Add in body-parser
* Setup route to show form
* Add basic unstyled form

#4.	Style the bets page
* Add a better header/title
* Make bets display in a grid

#5.	Style the Navbar and Form
* Add navbar to all templates
* Style the new bet form

#6.	Add Mongoose
* Install and configure mongoose
* Setup bet model
* Use bet model inside of our routes

#7.	Show Page
* Review the RESTful routes we’ve seen so far
* Add bet type to our bet model
* Show db.collection.drop()
* Add a show route/template

##RESTFUL ROUTES
Name		url		verb		description
INDEX		/dogs		GET		Display a list of all dogs
NEW 		/dogs/new	GET		Displays form to make a new dog
CREATE		/dogs		POST		Add new dog to DB
SHOW		/dogs/:id	GET		Shows info about one dog

#8. Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly 

#9. Add seeds file
* Add a seeds.js file
* Run the seeds file every time the server starts

#10. Add the Comment model!
* Make our errors go away!
* Display comments on bet show page

#11. Comment New/Create
* Discuss nested routes
* Add comment new and create routes
* Add the new comment form