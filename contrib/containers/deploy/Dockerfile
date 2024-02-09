FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="elevenchain Developers <dev@elevenchain.org>"
LABEL description="Dockerised elevenchain, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/elevenchain

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} elevenchain && \
    useradd -u ${USER_ID} -g elevenchain -s /bin/bash -m -d /home/elevenchain elevenchain && \
    mkdir /home/elevenchain/.elevenchain && \
    chown ${USER_ID}:${GROUP_ID} -R /home/elevenchain

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER elevenchain

VOLUME ["/home/elevenchain"]

EXPOSE 15967 9999 25967 25968

WORKDIR /home/elevenchain
