FROM python:slim

RUN apt-get update \
    && apt-get install -y python3-setuptools-git \
    && pip3 install --upgrade pip \
    && pip3 install setuptools \
    && pip3 install git+https://github.com/llm-workflow-engine/llm-workflow-engine

VOLUME ["/root/.local/share/llm-workflow-engine"]
