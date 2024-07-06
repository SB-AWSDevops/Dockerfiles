ARG version
FROM almalinux:${version}

# Display all *release files during the build process
RUN cat /etc/os-release

# Use shell form to execute cat /etc/*release when the container starts
CMD ["cat", "/etc/os-release"]

ARG course
RUN echo "course is ${course}"
