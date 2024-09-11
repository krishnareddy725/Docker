FROM almalinux:8

# Define a default value for the username argument
ARG username=myuser

# Add a new user with a home directory
RUN useradd -m $username

# Switch to the new user
USER $username

# Define the default command
CMD ["sleep", "100"]
