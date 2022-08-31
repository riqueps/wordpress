## Push sample wordpress to Epinio
```
cd $(mktemp -d) && git clone --depth=1 https://github.com/riqueps/wordpress && cd wordpress && \
	epinio push -n sample-wordpress -e BP_PHP_VERSION=8.0 -e BP_PHP_SERVER=nginx -e BP_PHP_WEB_DIR=wordpress
```