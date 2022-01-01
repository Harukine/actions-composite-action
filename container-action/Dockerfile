# Container image to run the code
FROM alpine:3.10

# Copy the code file to the container root
COPY docker-action.sh /docker-action.sh

# execute code file when container starts
ENTRYPOINT ["/docker-action.sh"]
