FROM almalinux
RUN yum install nginx unzip -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://templatemo.com/tm-zip-files-2020/templatemo_588_ebook_landing.zip /tmp/
RUN cd /tmp/
RUN unzip templatemo_588_ebook_landing.zip
RUN cp -r templatemo_588_ebook_landing/* /usr/share/nginx/html 
CMD [ "nginx","-g","daemon off;" ]