# Version
Compatible with Rasa Open Source version 3.x

# Rasa Subscribe Bot
This assistant is based on the [Rasa Playground Bot](https://rasa.com/docs/rasa/playground/), which showcases the implementation of a newsletter subscription form.

It uses a form to collect a user's email address and subscribe them to a newsletter.

## Running the assistant

1. If you are using the pre-prepared Gitpod workspace image, enter the preset venv environment:

``source venv/bin/activate``

2. Run the action server on a new terminal window:

``rasa run actions``

3. Return to the first terminal window and start the assistant on the command line:

``rasa shell``
