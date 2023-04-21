Generate the static site:
`pelican content`

Run the local server:
`pelican --listen`

Deploy to GH Pages:

```
$ pelican content -o output -s pelicanconf.py
$ ghp-import output -b gh-pages
$ git push git@github.com:BenBagBag/BenBagBag.github.io.git gh-pages:master
```
