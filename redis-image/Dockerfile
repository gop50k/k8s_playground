# 文法: Dockerfileにおける指示 指示の対象物
# From ベースとして使用する image
# OSを DLすると決める箇所, Linux distribution
FROM alpine

# Step2: Download and install dependency
# From の imageに対して追加で行う処理
# docker build 時に実行する処理
# apache pkgをalpineに対してupdate
RUN apk add --update redis

# Step3: Tell the image what to do when it starts as container
# docker run 時に実行する処理
CMD ["redis-server"]
