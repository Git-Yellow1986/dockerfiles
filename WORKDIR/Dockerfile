FROM almalinux:9
RUN mkdir /tmp/docker
# RUN cd /tmp/docker --> here RUN cd will not work as expected
WORKDIR /tmp/docker   
RUN pwd
RUN echo "Hello" > hello.txt 
CMD [ "sleep", "100" ]
