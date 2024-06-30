# Đồ án cuối kỳ: môn lập trình cho trí tuệ nhân tạo

- Nguyễn Minh Trường - 23C15016

## table of contents

- [Đồ án cuối kỳ: môn lập trình cho trí tuệ nhân tạo](#đồ-án-cuối-kỳ-môn-lập-trình-cho-trí-tuệ-nhân-tạo)
  - [table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Hướng dẫn dowload dataset + build + train + predict](#hướng-dẫn-dowload-dataset--build--train--predict)
    - [cách mở project](#cách-mở-project)
    - [Download dataset](#download-dataset)
    - [train, build trên từng models](#train-build-trên-từng-models)
    - [kết thúc](#kết-thúc)


## Requirements

- docker
- vscode
- vscode extensions [ms-vscode-remote.remote-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- nvidia driver (not required)

## Hướng dẫn dowload dataset + build + train + predict

### cách mở project

1. Clone project
2. Mở project bằng vscode
3. `ctrl`+`P` sau đó gõ `> dev container: Reopen in container` sau đó nhấn `Enter`
4. đợi containter build xong 
5. mở console trong vscode `Ctrl`+`Shift`+`F`
gõ `!nvidia-smi` để check xem đã cài cuda hay chưa


### Download dataset

- download datasets [mvtec_anomaly_detection.tar.xz](https://drive.google.com/file/d/1WrI6F5tnK2UsBMI7E3Zs-BbLCZhcvbFz/view?usp=sharing)
để vào thư mục [./dataset/](./dataset)

- dùng lệnh `unzip dataset/mvtec_anomaly_detection.tar.xz -d dataset/mvtec_anomaly_detection`

### train, build trên từng models

1. mở folder `final-project/yolo/`
2. Mở và chạy tuần tự các file:` data-processing.ipynb`, `object-detection.ipynb` 
3. xong

> *các model DETR, Faster-RCNN chạy tương tự*

### kết thúc

- cảm ơn thầy và các bạn
