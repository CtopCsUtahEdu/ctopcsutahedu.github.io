# ctopcsutahedu.github.io
CTOP Website

## Building
You need to install the Pelican Python module:

* `python3 -m pip install 'pelican[markdown]'`

Within the `/site` directory you can build the site with:

* `pelican content

This places the finished website files in the `/docs` directory. You can update the site with:

* `git add -A /docs`
* `git commit -m 'Your Message Here'`
* `git push origin publish`
