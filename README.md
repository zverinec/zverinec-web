# Zvěřinec website

<https://zverinec.fi.muni.cz/>

This repository contains website sources for _Friends of Nordic Animals
Association at FI MU_ web.

## Development

This page is served as static page. It is built using
[Jekyll](https://jekyllrb.com/).

## Toolchain setup

```bash
$ bundle install
```

## Web build

 * `$ make build` to build web to `_site` directory.
 * `$ make server` to serve webpage on localhost.

### Deployment

This repository is automatically deployed on push to GitHub to
<https://zverinec.fi.muni.cz/>.
