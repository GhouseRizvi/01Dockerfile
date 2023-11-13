FROM almalinux
RUN yum install wget zip unzip nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN cd /tmp/
RUN wget https://templatemo.com/tm-zip-files-2020/templatemo_591_villa_agency.zip
RUN unzip templatemo_591_villa_agency.zip
RUN cp -r templatemo_591_villa_agency/* /usr/share/nginx/html
COPY test.html /usr/share/nginx/html

