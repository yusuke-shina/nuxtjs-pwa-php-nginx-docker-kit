FROM jwilder/nginx-proxy:v0.9.0
COPY ./certs /etc/nginx/certs
RUN { \
  echo 'server_tokens off;'; \
  echo 'client_max_body_size 100m;'; \
  } >> /etc/nginx/conf.d/default.conf
