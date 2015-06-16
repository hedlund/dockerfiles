FROM ubuntu:trusty
MAINTAINER henrik@hedlund.im

# Set the locale
RUN locale-gen en_US.UTF-8  
ENV LANG en_US.UTF-8  
ENV LANGUAGE en_US:en  
ENV LC_ALL en_US.UTF-8  

# Set the timezone
RUN echo "Europe/Oslo" > /etc/timezone

# Install curl
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y curl
