# Manjaro Nemomobile Stable Edition
[![iso_build](https://github.com/jmlich/nemomobile/workflows/image_build/badge.svg)](https://github.com/jmlich/nemomobile/actions)

## description

Stable branch for Nemomobile of Manjaro Linux for the Pinephone

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/jmlich/nemomobile/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d pinephone -e nemomobile -v dev-20210227 -b unstable`

## credentials

```
user: manjaro
password: 123456
```

### links

- [halium images](https://github.com/manjaro-libhybris/image-ci)