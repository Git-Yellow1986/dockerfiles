ARG version="latest"
FROM almalinux:${version:-9}
ARG author="DevOps Engineer" \
    version="1.0" \
    duration = "24hrs"
ENV duration = $duration
RUN echo "Author: $author"
RUN echo "Version: $version"
RUN echo "duratio: $duration"
CMD [ "sleep", "100" ]
