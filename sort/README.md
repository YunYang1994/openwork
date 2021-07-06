- [博客地址：经典目标跟踪 sort 算法代码解析]

### 安装依赖

- filterpy==1.4.5
- scikit-image==0.17.2
- lap==0.4.0


### 使用说明

```bashrc
$ wget https://motchallenge.net/sequenceVideos/PETS09-S2L1-raw.mp4 -O data/train/PETS09-S2L1/PETS09-S2L1-raw.mp4
$ ln -s data mot_benchmark
$ mkdir -p ./data/train/PETS09-S2L1/img1/ 
$ ffmpeg -i ./data/train/PETS09-S2L1/PETS09-S2L1-raw.mp4 ./data/train/PETS09-S2L1/img1/%06d.jpg
$ python sort.py --display
```
 
