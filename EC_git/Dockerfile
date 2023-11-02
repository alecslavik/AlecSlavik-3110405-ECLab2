# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY sample.c .
# Compile the C program
RUN gcc -o sample sample.c
# Set the command to run when the container starts
CMD ["./sample"]