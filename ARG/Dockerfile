ARG version=9
FROM almalinux:$version
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
WORKDIR /app
#here user1 is key, someuser is default value
ARG USERNAME=Sivakumar
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /app/devops.txt
CMD ["sleep", "100"]