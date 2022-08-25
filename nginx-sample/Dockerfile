FROM nginx:latest

RUN rm /etc/nginx/nginx.conf 

COPY /etc/nginx/nginx.conf /etc/nginx/nginx.conf

COPY /*.html /nginx-sample/html/

ENV PORT=80

EXPOSE 80

# docker build -t {username}/{projname}
# docker run -p {localport}:{dockerport} {imageid}