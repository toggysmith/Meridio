# Instructions

## Dependencies

You will need to first install all of the dependencies.

Start a terminal instance in the root of the project and run `pip install -r requirements.txt` to install all of the required Pip dependencies.
Next run `cd meridio/core` and then `npm install` to install all of the required Node dependencies.

## Tailwind CSS

In your current terminal instance, run `npx tailwindcss -i ./static/src/input.css -o ./static/src/output.css --watch`. This will start the Tailwind CLI which will watch for Tailwind CSS changes in the HTML templates and update the output CSS file.

## Django

Keep the current terminal instance running and open a new instance in the root of the project again. Run `cd meridio` and then `python manage.py runserver` to start the Django server. If you go to the address it says, you should be able to see the project in action.
