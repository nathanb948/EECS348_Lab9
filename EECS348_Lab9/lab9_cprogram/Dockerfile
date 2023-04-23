# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY Score_calc.c .
# Compile the C program
RUN gcc -o Score_calc Score_calc.c
# Set the command to run when the container starts
CMD ["./Score_calc"]