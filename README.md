<a href="https://github.com/TryGhost/Ghost"><img src="https://cloud.githubusercontent.com/assets/120485/6622822/c4c639fe-c8e7-11e4-9e64-5bec06c8b4c3.png" alt="Ghost" /></a>
<a href="https://travis-ci.org/TryGhost/Ghost"><img align="right" src="https://travis-ci.org/TryGhost/Ghost.svg?branch=master" alt="Build status" /></a>

# [Ghost](https://github.com/TryGhost/Ghost) on [Heroku](http://heroku.com)

Ghost is a free, open, simple blogging platform. Visit the project's website at <http://ghost.org>, or read the docs on <http://support.ghost.org>.

## Deploying on Heroku

To get your own Ghost blog running on Heroku, click the button below:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/prashannth/ghost-heroku)

Fill out the form, and you should be cooking with gas in a few seconds.

### Things you should know

- After deployment, visit the admin area at `YOURAPPNAME.herokuapp.com/ghost` to set up your blog.

- Your blog will be publicly accessible at `YOURAPPNAME.herokuapp.com`.

- To make changes to your Ghost blog (like adding a theme to the `/content` directory, for instance), clone your blog locally using the [Heroku Toolbelt](https://toolbelt.heroku.com/):

  ```sh
  heroku git:clone --app YOURAPPNAME
  ```


# Staying Up to Date

When a new version of Ghost comes out, you'll want to look over these [upgrade instructions](http://support.ghost.org/how-to-upgrade/) for what to do next.

You can talk to other Ghost users and developers in our [public Slack team](https://ghost.org/slack/) (it's pretty awesome). We have a public meeting every Tuesday at 5:30pm UK time.

New releases are announced on the [dev blog](http://dev.ghost.org/tag/releases/). You can subscribe by email or follow [@TryGhost_Dev](https://twitter.com/tryghost_dev) on Twitter, if you prefer your updates bite-sized and facetious.

:saxophone::turtle:


# Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the [MIT license](LICENSE).
