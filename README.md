Google App Engine + zc.buildout template
===========================
[![Build Status](https://travis-ci.org/Trii/appengine-buildout-template.svg?branch=master)](https://travis-ci.org/Trii/appengine-buildout-template)

Template project for using zc.buildout with Google App Engine projects

### To initialize your project

```sh
$ python bootstrap-buildout.py
$ ./bin/buildout
```

### Now launch the app!

```sh
$ ./bin/dev_appserver
```

Enjoy

#### Made possible by the following recipes
* zc.buildout
* zc.recipe.egg
* appfy.recipe.gae
* pbp.recipe.noserunner



