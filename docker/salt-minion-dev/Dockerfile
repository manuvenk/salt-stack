#USE BASE IMAGE
FROM saltstack/salt

RUN mkdir -p /etc/salt/minion.d; echo "master: master" > /etc/salt/minion.d/master.conf; \
    echo "salt-minion-dev" > /etc/salt/minion_id


#CMD ["salt-minion","-d"]
EXPOSE 4506