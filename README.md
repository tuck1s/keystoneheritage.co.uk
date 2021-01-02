# keystoneheritage.co.uk static site

## Preview

The markdown files are in folder `source`.

```
cd source
hugo server
```

## Build

The html is generated using [Hugo](https://gohugo.io/) back into the `/docs` directory, for serving via [Github Pages](https://pages.github.com/).

```
cd source
hugo -D --destination ../docs
```