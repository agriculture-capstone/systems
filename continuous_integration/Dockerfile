FROM jenkinsci/blueocean

USER root
COPY sudoers /etc/
RUN apk update && apk add sudo && \
	git config --global user.email boresha.core@gmail.com && \
    git config --global user.name boreshabuilder

USER jenkins

