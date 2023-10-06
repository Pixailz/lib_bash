# lib_bash
My library for bash scripts / progams

## How to install

> CLI

`bash -c "$(curl -sL https://bit.ly/lib_bash)"`

> In script

```bash
# install lib_bash
DIR_LIB_BASH="${HOME}/.local/lib/lib_bash"
[ ! -d "${DIR_LIB_BASH}" ] && \
	bash -c "$(curl -sL https://bit.ly/lib_bash)"

# source .config
[ ! "${LIBBASH_SOURCED}" ] && . "${DIR_LIB_BASH}/.config"
```

## Rules of the lib

1. each function must be commented like this [template](./rsc/template/comment.fonction.tmp)
2. each part of the lib have is own include file AND can be included multiple times
3. for more details on each function of the lib, test [dir](./test/) is here to help you

## TODO

1. rewrite how parsing work
  - should use getopt in a while loop

### ANDROID

####  FULL STEP, FOR A WEAPONIZED PHONE

1. install twrp
4. install system
5. boot, and do install "Welcome" page
6. reboot to twrp
7. install magisk
8. install nethunter

#### TODO

1. build nethunter package for android 13 lineage
