FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://templatemo.com/tm-zip-files-2020/templatemo_588_ebook_landing.zip /tmp/
RUN cp -r /tmp/templatemo_588_ebook_landing/* /usr/share/nginx/html 
CMD [ "nginx","-g","daemon off;" ]