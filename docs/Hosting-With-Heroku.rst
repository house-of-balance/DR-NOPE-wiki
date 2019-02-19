 Making a Heroku account
^^^^^^^^^^^^^^^^^^^^^^^

To host the bot on Heroku we need to make an account on Heroku! You can
do this over `here.`_

Get the repo
^^^^^^^^^^^^

Assuming you already have a GitHub account, download the master branch
(doesn't support heroku yet) or the dev-v2 branch and configure the
config.

   configure the config

Making the Heroku app
^^^^^^^^^^^^^^^^^^^^^

Now we get to some dirty stuff, make an app on `the Heroku dashboard`_
and name it whatever you want.

The github repo
^^^^^^^^^^^^^^^

Why I needed the "Get the repo" section

So make a new github repo, and upload the bot files to it. Simple,
right?

Managing the app
^^^^^^^^^^^^^^^^

So now you connect the GitHub repo to the app. Manage the app like
normal `over here`_ and go to the "Deploy" tab. Then connect your github
account to the repo, blah blah blah.

Now go to the "Resources" tab and select the pencil next to

::

   worker: node bot.js

and flip the switch.

Boom! Your bot should now be online!

.. _here.: dashboard.heroku.com
.. _the Heroku dashboard: https://dashboard.heroku.com/new-app
.. _over here: dashboard.heroku.com
