FROM jenkins/jenkins

ARG user=jenkins
ARG group=jenkins
ARG uid=1000
ARG gid=1000
ARG projectOrigin=/var/project_origin
ARG projectWww=/var/project_www
USER root
RUN mkdir -p  ${projectOrigin} && chown ${uid}:${gid} ${projectOrigin}
RUN mkdir -p  ${projectWww} && chown ${uid}:${gid} ${projectWww}
