ARG version
FROM almalinux:${version:-9}
ENV course="Devops" \
    trainer="sivakumar" \
    duration="120hrs"
ARG USERNAME=Sivakumar  
ENV USERNAME=$USERNAME 
RUN echo "hello user: ${USERNAME} , image version: ${version}" > /tmp/devops.txt
CMD ["sleep","100"]
