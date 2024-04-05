FROM nginx
RUN rm -rf /usr/share/nginx/html/index.hrml
COPY roboshop.conf /etc/nginx/default.d
ADD static /usr/share/nginx/html/