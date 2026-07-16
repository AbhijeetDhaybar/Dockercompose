FROM nginx:latest
LABEL "peoject"="vprofile"
LABEL "Author"="abhi"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/vproapp.conf