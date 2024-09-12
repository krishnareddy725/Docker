ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG course
ARG trainer
RUN echo "course:${course}, Trainer:${trainer}"
ENV course = ${course}
ENV Trainer = ${trainer}
CMD ["sleep","100"]