# 运行镜像,并进入


在docker的linux环境运行python代码

``` docker
docker pull python:alpine

docker run -it -v /d/1.source/pythonpath/python-learning/utils:/data1 python:alpine /bin/sh

python data1/zone.py
```
- windows文件路径:/d/1.source/pythonpath/python-learning/utils/zone.py

zone.py

``` python
from datetime import datetime

print(datetime.now())

```

:ribbon: :ribbon: 读后有收获可以请作者喝咖啡：

<img src="https://images.gitee.com/uploads/images/2021/1226/125920_9f0e6151_9674723.png" width="60%"/>