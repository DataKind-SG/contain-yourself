FROM jupyter/minimal-notebook:9e056d61b7a5

COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt
COPY . /tmp/

