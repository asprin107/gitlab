FROM ubuntu:18.04

USER root

RUN apt-get update
RUN apt-get install -y curl openssh-server
#RUN apt-get install -y ca-certificates tzdata perl
#RUN curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.deb.sh | sudo bash
#RUN EXTERNAL_URL="http://gitlab.example.com" apt-get install gitlab-ee

CMD /bin/sh