FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.com
RUN rm -f /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST="catalogue"