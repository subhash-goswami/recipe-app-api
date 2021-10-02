## recipe-app-api

**Create a API's to manage the recipe and ingredients and add Tag on details of particular user**
### Technologies used:
- Python (Django)
- SQLite database

### Task:
- Create an RESTful API's to manage the recipe and the ingredients items.
- RESTful API for `User`, url 'api/user/':
	-Create new user `['email', 'password', 'name']`

- RESTful API for `Ingredient`, url 'api/recipe/ingredient':
	- Get ingredients detail using ingredient name
	- Create new ingredients `[name, user]`
	- Update ingredient detail using name
	- Delete ingredient using name
	- Get all the ingredient in list

- RESTful API for `Tag`, url 'api/recipe/tags':
	- Get Tag detail using Tag name
	- Create new Tag `[name, user]`
	- Update Tag detail using name
	- Delete Tag using name
	- Get all the Tag in list

- RESTful API for `recipe`, url 'api/recipe/recipe' :
	- Get the recipe detail using recipe name
	- Create new recipe `[user, title, time_minutes, price, link, ingredient, tag, image]`
	- Delete recipe using recipe name
	- Get all the recipe in list

 **`Note:`**

- Recipe name, Ingredient name, Tag name and username must be unique
- Store all details in SQLite3 database with the help of SQL-Alchemy
- Create Test cases for all modules
- API response must be in JSON structure with proper status code
- User have Token so that each time token need to be verify
