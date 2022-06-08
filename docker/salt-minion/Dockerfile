#USE BASE IMAGE
FROM saltstack/salt

#INSTALL SERVICE STARTING BASIC COMMAND
RUN apk add openrc

RUN mkdir -p /etc/salt/minion.d; echo "master: master" > /etc/salt/minion.d/master.conf; \
    echo "minion1" > /etc/salt/minion_id


#CMD ["salt-minion","-d"]
EXPOSE 4506
    
