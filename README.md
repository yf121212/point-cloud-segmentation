# Point Cloud Segmentation

<img src="https://github.com/soumik12345/point-cloud-segmentation/workflows/tests/badge.svg" alt="build-failing">

## Running using Docker

- Build image using `docker build -t point-cloud-image .`

- Run Jupyter Server using `docker run -it --gpus all -p 8888:8888 -v $(pwd):/usr/src/point-cloud-segmentation point-cloud-image`
