# Stella
A modular telegram Python bot running on python3 with an sqlalchemy database.

Originally a simple group management bot with multiple admin features, it has evolved, becoming extremely modular and 
simple to use.

Can be found on telegram as [Stella](https://t.me/missStella_robot).

Stella and I are moderating a [support group](https://t.me/NoobiezHub), where you can ask for help setting up your
bot, discover/request new features, report bugs, and stay in the loop whenever a new update is available. Of course
I'll also help when a database schema changes, and some table column needs to be modified/added. Note to maintainers that all schema changes will be found in the commit messages, and its their responsibility to read any new commits.

Join the [news channel](https://t.me/itzMeZeus) if you just want to stay in the loop about new features or
announcements.

Alternatively, [find me on telegram](https://t.me/ITzMeZeus)! (Keep all support questions in the support chat, where more people can help you.)

To deploy me on heroku, use below button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Im-zeus/Stella)

## Starting the bot.

Once you've setup your database and your configuration (see below) is complete, simply run:

`python3 -m Stella`


## Setting up the bot (Read this before trying to use!):
Please make sure to use python3.6, as I cannot guarantee everything will work as expected on older python versions!
This is because markdown parsing is done by iterating through a dict, which are ordered by default in 3.6.
