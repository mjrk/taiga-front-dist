# Taiga Front #

This branch is a compiled version of https://github.com/mjrk/taiga-front,
branch `5.5.5.change-project`

## Installation ##

* Clone the repo
* Expose the `dist` directory under a static file web server
* Rename dist/js/conf.example.json to conf.js if you want to change settings

More information about the different installation methods (production, development, vagrant, docker...) can be found here http://taigaio.github.io/taiga-doc/dist/#_installation_guide.


## For Devs ##

To regenerate branches ```master``` and ```stable```

```
git checkout master; node dist.js master
git checkout stable; node dist.js stable
```

## Community ##

[Taiga has a mailing list](http://groups.google.com/d/forum/taigaio). Feel free to join it and ask any questions you may have.

To subscribe for announcements of releases, important changes and so on, please follow [@taigaio](https://twitter.com/taigaio) on Twitter.
