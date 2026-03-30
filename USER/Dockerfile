FROM almalinux:9
RUN dnf install nginux -y
CMD ["nginux", "-g", "daemon off;"]
# root access requried to create user ot install packages
RUN useradd roboshop
USER roboshop
CMD ["sleep","100"]
