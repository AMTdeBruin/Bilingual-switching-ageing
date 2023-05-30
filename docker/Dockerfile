FROM rocker/verse:4.3.0

RUN apt-get update -qq
RUN apt-get -y install git

RUN install2.r –error \
--deps TRUE \
rmarkdown \
lme4 \
lmerTest \
bookdown \
rstatix