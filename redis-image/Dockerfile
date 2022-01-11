#文法: Dockerfileにおける指示 指示の対象物
# From ベースとして使用する image
FROM alpine

# Step2: Download and install dependency
# From の imageに対して追加で行う処理
RUN apk add --update redis

# Step3: Tell the image what to do when it starts as container
CMD ["redis-server"]
