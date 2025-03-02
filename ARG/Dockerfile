FROM almalinux:9
ENV course="devops with AWS" \
    trainer="siva" \
    duration="120hrs"
ARG ${username:-some_user}
#here user1 is key and someuser is default value
RUN echo "hello ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]