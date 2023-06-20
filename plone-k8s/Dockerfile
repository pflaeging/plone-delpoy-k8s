FROM docker.io/plone/plone-backend:6.0

USER 0

RUN chgrp -R root /app /data && \
    chmod -R g=u /app /data

USER 177721:0