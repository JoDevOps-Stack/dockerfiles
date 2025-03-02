ARG version 
FROM almalinux:${version:-9}
ENV course="devops with AWS" \
    trainer="siva" \
    duration="120hrs"
ARG USERNAME=Sivakumar
RUN echo "hello user: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]