FROM  rabbitmq:4.0.5-management

ADD rabbitmq.conf /etc/rabbitmq/rabbitmq.conf
ADD definitions.json /etc/rabbitmq/definitions.json
RUN chmod +rwx /etc/rabbitmq/rabbitmq.conf
RUN chmod +rwx /etc/rabbitmq/definitions.json