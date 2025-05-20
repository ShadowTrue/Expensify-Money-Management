FROM golang:1.24

# Set working directory
WORKDIR /workspace

# Optional: install common dev tools
RUN apt-get update && apt-get install -y curl git

# Optional: copy your code (but dev containers usually mount it instead)
# COPY . .

# Set environment vars
ENV GO111MODULE=on

CMD [ "sleep", "infinity" ]


