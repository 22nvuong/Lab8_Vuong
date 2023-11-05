# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY lab5_program2.c .
# Compile the C program
RUN gcc -o lab5_program2 lab5_program2.c
# Set the command to run when the container starts
CMD ["./lab5_program2"]