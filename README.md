# databaker_docs
A sphinx generator repo for databaker documentation.

the "html version" of this repo. Can be found here:
https://ons-opendata.github.io/databaker_docs/



## Usage

Sphinx uses reStructuredText as a markup language for creating documention.

This repo contains the .rst files that make up the mini-site, as well as a shell script to "publish" them.

To update the documentation you install sphinx

`pip install sphinx`

Then change the relevent .rst file (or add some new ones) and run the publish.sh shell script. That will update this repo as well as the branch that "holds" the html version (the gh-pages branch).

## DO NOT COMMIT TO THIS REPO IN THE USUAL MANNER!

....as this can put the master and gh-pages branches out of sync. Literally just make your changes and run /publsh.sh.
