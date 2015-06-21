# samuelgreen.org 

This is the source code for [samuelgreen.org](http://samuelgreen.org). It's branched from the source for [shapeshed.com](http://shapeshed.com), and it's build on [flim](https://github.com/shapeshed/flim), a static site generator.

## Installation

    npm install

## Site generation

    make build

## Deployment

This site is deployed on GitHub pages. Deployment via:
	
	make deploy

Deploys the static build to its GitHub repository. 

## OSX specific notes

If you are on OSX the `Makefile` uses GNU sed and GNU md5sum. To install these on a Mac do

    brew install --default-names gnu-sed
    brew install md5sha1sum
