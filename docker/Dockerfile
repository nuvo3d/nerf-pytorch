FROM pytorch/pytorch:1.9.0-cuda11.1-cudnn8-runtime
MAINTAINER Cristian Duguet <c@nuvo.cam>
RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6  -y
RUN pip install matplotlib numpy imageio imageio-ffmpeg configargparse tensorboard tqdm opencv-python
EXPOSE 8888
CMD ["bash"]