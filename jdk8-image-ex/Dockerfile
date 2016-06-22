FROM frolvlad/alpine-oraclejdk8:slim

#VOLUME /mnt
WORKDIR /mnt

ADD Main.java .

ENTRYPOINT [ "sh" ]
CMD [ "-c", "javac Main.java && java Main" ]

