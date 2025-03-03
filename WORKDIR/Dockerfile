FROM almalinux:9
RUN useradd Prakash
USER Prakash
RUN mkdir /tmp/work-dir-demo
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "Hello from WORK DIR" > hello.txt
CMD ["sleep", "100"]