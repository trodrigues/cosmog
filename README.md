*Get in the bag Nebby*

# Cosmog

Cosmog is a React based starter kit and/or static site generator I've built for my own personal needs.

At the moment it's not installable via npm and the way to run it/use it is essentially to fork/copy whatever is necessary from this repo, remove what you don't need and adapt it to your needs.

It's named after [this lovely little fella](http://www.pokemon-sunmoon.com/en-ca/pokemon/cosmog/) because he's also all universal and shit.

I also make no apologies for any bag related jokes.

# Why another SSG/Starter Kit/whatever?

Because most of the things out there do either too much, too little, or weird stuff I don't need or had to always tweak/change to work the way I wanted.

As such, I've decided to put something together from scratch, adapted to my needs and using the tools I like and want to use.

I built this mostly for me and my own purposes, but as others might be curious or might find it useful, I'm putting it out there. **However, I don't intend on supporting this for anyone else.**

# What's in the bag?

- React.js
- React Router
- Hapi
- Webpack
- CSS Modules
- PostCSS

# What can it do?

With little changes (mostly just removing what's not necessary), this kit can be used for:
- Client side only webapps
- Server rendered only webapps
  - Simply don't include the JS bundle on the index.html template
- Universal webapps
- Statically generated websites
  - Use `bin/static.js` to statically render markdown files in a given directory. Directory structure in the `content` directory is respected.

# Developing with Docker

A `Dockerfile` and an example `docker-compose.yml` file are included.

Simply running `docker-compose up cosmog-client` should get a local development environment up and running.