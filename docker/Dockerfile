FROM nvcr.io/nvidia/tensorrt:19.07-py3

RUN apt-get update
RUN apt-get install -y libsm6 libxrender1 libxext-dev sudo

RUN pip install Cython opencv-python

RUN useradd -m myuser
USER myuser
WORKDIR /home/myuser
