FROM ubuntu:latest
COPY sources.list /etc/apt/sources.list

RUN apt-get update && apt-get install -y --no-install-recommends vim
	
RUN apt-get install -y net-tools && apt-get install -y ssh

EXPOSE 22
CMD ["ifconfig"]