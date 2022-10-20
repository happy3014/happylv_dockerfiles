# happylv_dockerfiles
编译一些常用的基础环境使用的镜像。

# 常用命令
```
# 登录
docker login ccr.ccs.tencentyun.com --username=100006233649

docker build -t ccr.ccs.tencentyun.com/happylv/kona11:v1 -f Dockerfile.tencent_kona11 .
docker build -t ccr.ccs.tencentyun.com/happylv/kona11_maven3:v1 -f Dockerfile.tencent_kona11_maven3 .
docker build -t ccr.ccs.tencentyun.com/happylv/kona11_maven3:v1_tencent -f Dockerfile.tencent_kona11_maven3 --build-arg MIRROR_TYPE=tencent .
docker build -t ccr.ccs.tencentyun.com/happylv/kona11_maven3:v1_aliyun -f Dockerfile.tencent_kona11_maven3 --build-arg MIRROR_TYPE=aliyun .
```
