FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# this instruction runs when someone use this image
ONBUILD COPY index.html /usr/share/nginux/html/index.html
CMD ["nginx","-g","daemo off;"]