ARG version
FROM almalinux:${version}

# Display all *release files during the build process
RUN cat /etc/*release

# Use shell form to execute cat /etc/*release when the container starts
CMD ["cat", "/etc/*release"]

ARG course
RUN echo "course is ${course}"
