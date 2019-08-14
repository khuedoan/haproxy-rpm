# Build HAProxy RPM from source with fpm and fpm-cookery

## Install fpm and fpm-cookery

```bash
# yum install ruby-devel gcc make rpm-build rubygems
# gem install --no-ri --no-rdoc fpm fpm-cookery
```

## Compile and create RPM package

```bash
# fpm-cook
```

## Install HAProxy

```bash
# cd pkg
# rpm -i haproxy-1.8.20-1.x86_64.rpm
# systemctl enable --now haproxy
```

## fpm-cookery documentation

https://fpm-cookery.readthedocs.io/en/latest/

## Acknowledgement

https://github.com/jordansissel/fpm

https://github.com/bernd/fpm-cookery

https://github.com/bernd/fpm-recipes
