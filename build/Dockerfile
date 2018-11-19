FROM mageia:5

ARG YATEVERSION=6.0.0-1

RUN curl -o /usr/src/yate-$YATEVERSION.mga5.x86_64.rpm http://yate.null.ro/tarballs/yate6/mga5/x86_64/yate-$YATEVERSION.mga5.x86_64.rpm
RUN rpm -Uhv /usr/src/yate-$YATEVERSION.mga5.x86_64.rpm
RUN systemctl enable yate

CMD [ "/bin/bash" ]