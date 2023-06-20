FROM docker.io/plone/plone-backend:6.0

USER 0

RUN chgrp -R 0 /app && \
    chgrp -R 0 /data && \
    chmod -R g=u /app && \
    chmod -R g=u /data

USER 177721:0