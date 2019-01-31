FROM docker.io/openshift/jenkins-2-centos7:v3.10
RUN yum -y install vim-common fakeroot
USER 0
ENTRYPOINT ["/usr/bin/dumb-init", "--"]
CMD ["/usr/libexec/s2i/run"]
