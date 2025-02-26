ARG version
FROM almalinux:${version}
ENV project="ansh" \
    environment="dev" \
    Docker="True"
RUN useradd ansh
ARG USERNAME=Sri
RUN echo "Hello ${USERNAME}" > /tmp/hello.txt
USER ansh
CMD ["sleep", "100"]
