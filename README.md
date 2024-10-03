# docker-quaker-kr-de

## MISSION

Code of the docker image from the website quaker-kr-de. It's static geneated code
by Hogo.

Used thema: [DPSG](https://themes.gohugo.io/themes/hugo-dpsg/)

## USE HUGO

To run local webserver enter:

```bash
hugo server --ignoreCache -D --source ./hugo/
```

And check

<http://127.0.0.1:1313>

### ABOUT USED THEME

See [DPSG](https://themes.gohugo.io/themes/hugo-dpsg/)

### DOCKER BUILD

Enter:

```bash
podman build .
```