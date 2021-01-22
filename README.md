# Python Tutorial For Flask
> This is a tutorial I went through while going through the Bottega course.
## Start the server
- Run the following commands in your terminal while in the `hello_flask` folder.
```
$ pipenv shell
(hello_flask) python app.py
```
- If you get an error saying it doesn't know about a package, you might need to install the packages, or you might not be in your `pipenv shell`
```
$ pipenv shell
(hello_flask) pipenv install
(hello_flask) python app.py
```
- Flask
  - https://flask.palletsprojects.com/en/1.1.x/
- Flask SQLAlchemy
  - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
- Flask Marshmallow
  - https://flask-marshmallow.readthedocs.io/en/latest/
- Marshmallow-sqlalchemy
  - https://marshmallow-sqlalchemy.readthedocs.io/en/latest/

  ## Fix Import Warnings
> With `VSCode` and `Pylance` you might need the following settings in order to let your `linter` and `code editor` know about your environment.
>Hop into your `pipenv shell` and copy the `path` where your `virtualenv` is located and apply it to a `.vscode/settings.json` file in the root of the project.  I have provided an `.vscode/example.settings.json` for your referance.
```json
{
  "python.pythonPath": "/YOUR_VIRTUALENV_PATH/bin/python3"
}
```