FROM coatldev/python:3.12-slim

COPY requirements.txt /tmp/requirements.txt

RUN set -eux; \
    \
    python -m pip install \
        --no-cache-dir \
        --requirement \
        /tmp/requirements.txt; \
    \
    rm -rf /tmp/*

CMD [ "/bin/bash" ]