# Front

Front project part in /front dir
With vite for building project
Run dev server with `npm run dev`

# Back

Back project part in /back dir
With poetry for managing python libs
* `poetry add <my_python_lib>` to add a new python lib
* `poetry run python manage.py runserver` to start django
* `poetry run black .`
* `poetry run isort .`
* `poetry run flake8 .`

## Database

Postgres with docker
Run with `docker compose up -d`

# TODO

## DB

Book:
* cover
* summary
* genre
* tags
* links to buy (url + icon ?)
* release date
* price

Price:
* value
* offer
* offer date start
* offer date stop

Author:
* name
* links social network (url + icon ?)
* books

User:
* name
* favorites
* books read

## Views

Current quarter:
* list of books
* classic list or mosaic (only cover ?)
* click on one book to display it

Book view:
* Book info tab
  * cover
  * links in a sort of label
  * informations: release date + genre + price + tag
  * summary
* Author info tab
  * name
  * links
  * list of books
Can put in favorites

Previous quarter:
* list of books

Next releases (not quarter related):
* list of books
* countdown

Current special offers:
* list of books

Extracts:
* list of extracts
* likes counters
* comment ?
* link to the book

Favorites:
* list of books