WorkCafe.in
===========

This repository hosts the [workcafe.in](http://workcafe.in) website.

The JavaScript, CSS and HTML files are the result of the [WorkCafe/app](https://github.com/WorkCafe/app) build.
Don't edit those files.

## Contributions

Edit the files inside the `api` repository and send a pull request.

The current version is `v1`.

### Adding your city

Edit the `api/v1/cities.json` file.

### Adding a new venue

The city venue files use GeoJSON format.
To find more about GeoJSON check [the GitHub help](https://help.github.com/articles/mapping-geojson-files-on-github).

If your city venue file exists, you should find it inside the `api/v1/locations/` folder.

You will want to edit it and append a new entry to `features`.

If you city does not exist, create a new one using the same filename as the city `id`.

Check the existing files for boilerplate data before creating a new file.
