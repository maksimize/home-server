FROM cptactionhank/netatalk

#RUN /usr/sbin/useradd maks
#RUN  echo 123 | passwd maks --stdin

RUN /usr/sbin/useradd maks   

RUN echo maks:123 | chpasswd
RUN echo root:123 | chpasswd

ADD apf.conf /etc/afp.conf

#CMD tail -f /etc/hosts
