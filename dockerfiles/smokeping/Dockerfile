FROM linuxserver/smokeping
MAINTAINER Bobbymac
COPY Targets /config/Target

EXPOSE 80 80

# The EXPOSE variable doesn't actually do anything but is intended to be a hint from the builder to the running.  The actual port gets bound with the docker run command  If you are only one port 80 service then 80:80 is fine.  In the event that you want to run multiple services then a loadbalancer will be needed 
