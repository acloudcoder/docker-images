FROM codefresh/cf-p4-plugin

EXPOSE #PORT

ENV NAME p4depot
ENV P4CONFIG .p4config
ENV DATAVOLUME /data
ENV P4PORT #IP-OR-URL:#PORT
ENV P4USER #USERNAME
ENV P4PASSWD #PASSWORD
RUN apt-get install -y zip unzip
CMD ["bash"]

#Create P4 Client
#p4 client -o my_client_2
#p4 set p4client=my_client
#p4 client
