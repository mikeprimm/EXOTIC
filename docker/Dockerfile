FROM python:3.10
RUN apt-get update && apt-get install -y && rm -rf /var/lib/apt/lists/* && pip install exotic==4.3.1
WORKDIR /work
ENTRYPOINT [ "/bin/bash"]
