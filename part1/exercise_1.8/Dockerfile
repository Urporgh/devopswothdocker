# Start from the ubuntu:20.04
FROM ubuntu:20.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the website.sh file
COPY website.sh .

# Install curl
RUN apt-get update && apt-get install curl -y

# Run the script
CMD ./website.sh
