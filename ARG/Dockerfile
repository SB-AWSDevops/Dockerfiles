ARG version
FROM almalinux:${version}

# Display all *release files during the build process
RUN cat /etc/os-release

# Use shell form to execute cat /etc/*release when the container starts
ARG course=devops
ENV place=vizag
RUN echo "course is ${course} and  place is ${place} "
CMD [ "sleep","100" ]
