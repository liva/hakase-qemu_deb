# build qemu debian package for hakase-qemu
## HowTo

$ docker build -t hakase-qemu_image .
$ docker run -it -d --name hakase-qemu_container hakase-qemu_image
$ docker cp hakase-qemu_container:/build-qemu/qemu_2.9.0-1_amd64.deb .