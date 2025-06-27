FROM coatldev/python:2.7.18-slim

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