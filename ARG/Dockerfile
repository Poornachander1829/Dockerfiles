ARG version
FROM almalinux:${version:-9}
ENV course="Devops with aws" \
    trainer="Shiva kumar reddy" \
    Duration="120 hrs"\
    source="online" \
    url='join devops.com'
ARG USERNAME=Sivakumar
ENV USERNAME=$USERNAME
RUN echo "Hello User:${USERNAME}, imager version: {version}" > /tmp/devops.txt
CMD ["sleep","100"]
