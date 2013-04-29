django-LARP-app
===============

A Django app for LARP GMs to run and manage applications for their game.

# Setup

 * Create a new Django project.
 * Move the `app/` directory to where your project's apps live.  
 * Add `app` and `django.contrib.messaging` to INSTALLED_APPS.
 * Configure email per the [Django docs](https://docs.djangoproject.com/en/dev/topics/email/). I generally sign up for a Gmail account for this purpose.
 * Edit `app/settings.py` with your game's info.
 * Create an `app/models.py` using `app/models.example.py` as an example.
 * Edit `app.html` to integrate with your game's app if there is one.

You have permission to use it, or derivatives thereof, for your game, subject to the following disclaimer:

THIS CODE COMES WITH NO WARRANTY OR PROMISE OF FUNCTIONALITY WHATSOEVER. IT IS ALMOST CERTAINLY INSECURE. IT MAY BREAK ON DAY EIGHT, REVEAL SECRETS TO YOUR PLAYERS, COMPROMISE YOUR SERVER, AND KICK YOUR PUPPY. NEITHER THE AUTHORS NOR THE MIT ASSASSINS' GUILD ASSUME ANY LIABILITY WHATSOEVER FOR ANYTHING YOU DO WITH THIS CODE.

Enjoy!

-ternus

4/13