# The-Birds

> WebGl演示网站因服务器带宽问题没有用docker部署，但是dockerfile测试过是可用的。

- [WebGl 部署]()

  - install Docker-ce

    > Centos
    >
    > ```shell
    > $ curl -fsSL https://get.docker.com -o get-docker.sh
    > $ sudo sh get-docker.sh
    > ```
    >
    > Others
    >
    > [docker.com install docker](https://docs.docker.com/install/linux/docker-ce/centos/#install-using-the-convenience-script)
    >
    > [aliyun install docker](https://yq.aliyun.com/articles/110806?spm=a2c4e.11153940.0.0.52027e291Wei2v)
    
  - run Docker image
  
    > ```shell
    > $ mkdir angryBird && cd angryBird && wget https://raw.githubusercontent.com/chengaoang/The-Birds/develop/dockerFile/Dockerfile && docker build -t angrybird:0.1 . && docker run -p 80:80 --name angrybirdcontainer angrybird:0.1
    > ```
  
- [Android & Windows 演示]()

  - 在 [releases](https://github.com/chengaoang/The-Birds/releases) 页面有演示程序

## TODO
- [x] write AngryBird.docx 20-03-02/20-03-16
