FROM docker.bintray.io/jfrog/jfrog-cli-go:latest
VOLUME /tmp
RUN mkdir -p /target && cd /target
ENV ARTIFACTORY_URL=#ArtifactoryURL
ENV ARTIFACTORY_USER=#Username
ENV ARTIFACTORY_PASSWORD=#Password

#Connect using => jfrog rt c rt-server-1 --url=$ARTIFACTORY_URL --user=$ARTIFACTORY_USER --password=$ARTIFACTORY_PASSWORD
#Copy artifact using => jfrog rt u #SOURCEPATHTOZIP  #DESTPATHTOZIP --url=$ARTIFACTORY_URL --user=$ARTIFACTORY_USER --password=$ARTIFACTORY_PASSWORD