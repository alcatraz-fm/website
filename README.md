# alcatraz.fm

our home on the web

## development

```sh
npm install  # install deps
gulp dev # run locally
```

with `gulp dev` you can modify .html and scss/ - page will live reload


## deploy

```
gulp
rsync -ravuP -e ssh css img vendor *.html *.css your-username@your-remote-server
```

# license

BSD-2
