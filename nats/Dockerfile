FROM nats
ADD config/nats-server.conf /etc/nats/
EXPOSE 4222 8222 6222
CMD ["--config", "/etc/nats/nats-server.conf"]