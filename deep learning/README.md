# Run

Date: 2025-05-07

## docker

```
docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/tensorflow-notebook:x86_64-2022-09-21
```

## local

Extraído del docker anterior.

```
apt-get install libblosc-dev
apt-get install libbrotli-dev
apt-get install libz-dev libblosc-dev liblzma-dev liblz4-dev libzstd-dev libpng-dev libwebp-dev libbz2-dev 
apt-get install libopenjp2-7-dev libjpeg-turbo8-dev libjxr-dev liblcms2-dev libcharls-dev libaec-dev libbrotli-dev libsnappy-dev libzopfli-dev libgif-dev libtiff-dev
apt-get install libdeflate-dev
apt-get install python3-venv python3.10-dev
```

```
# ¿apt-get install python-dev?
# Crea virtual env e instalar requeriments
pip3 install -r pre.requeriments.txt
pip3 install -r requeriments.txt
```

## Problemas con imagecodecs==2022.8.8

```imagecodecs``` no es necesario para estos notebooks

Librerías probadas antes de la instalación:

```
sudo add-apt-repository ppa:strukturag/libde265
sudo add-apt-repository ppa:savoury1/multimedia
sudo apt-get update

apt-get install -y \
    cython \
    libbrotli-dev \
    libbz2-dev \
    libblosc-dev \
    libcharls-dev \
    libgif-dev \
    libjxr-dev \
    liblcms2-dev \
    liblerc-dev \
    libaec-dev \
    libavif-dev libaom-dev libdav1d-dev   libyuv-dev libxml2-dev \
    libdeflate-dev \
    libheif-dev libde265-dev x265 \
    libjpeg-turbo8-dev \
    libjxl-dev \
    liblzma-dev \
    libpng-dev \
    libtiff-dev \
    libwebp-dev \
    liblz4-dev \
    libopenjp2-7-dev \
    libsnappy-dev \
    zlib1g-dev \
    libzopfli-dev \
    libzstd-dev
```
