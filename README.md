# cdn

`git clone [https://github.com/gradyskyi/cdn](https://github.com/gradyskyi/cdn)`

`docker-compose up`

visit [http://172.21.0.6/images/image-01.png](http://172.21.0.6/images/image-01.png)

or check ip for cdn container:

`docker inspect cdn-balancer | jq '.[0].NetworkSettings.Networks.cdn_default.IPAddress'`

And try to change balancing methods, uncomment in upstream cdn