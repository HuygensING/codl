Downloaded Wordpress site with:

```
wget -P . -mpck --user-agent="" -e robots=off --wait 1 -E https://www.codl.nl/
```

Copied contents of webroot to lighttpd container (see docker/Dockerfile)

Pushed docker image to private repository

Deployed image in Kubernetes (see k8s/)