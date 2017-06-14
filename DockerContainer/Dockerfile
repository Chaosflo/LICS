FROM greyltc/lamp

EXPOSE 80

ADD ../WebApp /srv/http

RUN chmod -R 770 ~/www; 
RUN sudo chgrp -R 33 ~/www