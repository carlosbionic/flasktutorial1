# Flask Tutorial Practice

Tutorial from [https://flask.palletsprojects.com/en/2.2.x/tutorial/](https://flask.palletsprojects.com/en/2.2.x/tutorial/)

## How to work with this repository

If you are using a virtual environment (for example for Windows 10):

`.\venv\Scripts\activate`

To run the Flask app with debug mode on (in this case the app is called `flaskr`):

`flask --app flaskr --debug run`

If you need to initialize the database (warning: this will erase all your previously recorded data from the app):

`flask --app flaskr init-db`

## Working on this steps 

(from [https://flask.palletsprojects.com/en/2.2.x/tutorial/next/](https://flask.palletsprojects.com/en/2.2.x/tutorial/next/))

* [x] A detail view to show a single post. Click a post’s title to go to its page.
* [x] Like / unlike a post.
* [x] Comments.
* [x] Tags. Clicking a tag shows all the posts with that tag.
* [x] A search box that filters the index page by name.
* [x] Paged display. Only show 5 posts per page.
* [x] Upload an image to go along with a post.
* [x] Format posts using Markdown.
* [x] An RSS feed of new posts.