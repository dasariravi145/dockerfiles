FROM nginx:1.29.7

RUN apt-get update && \
    apt-get install -y iputils-ping

#CMD ["ping","google.com"]

ENTRYPOINT ["ping","google.com"]