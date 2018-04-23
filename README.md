# ico-spider

download ICO source code  from [etherscan](https://etherscan.io/)

## how to run 
### centos7 为例
+ `yum install -y python-pip python-devel`
+ `yum groupinstall -y "Development tools"`
+ `pip install -r  requirements.txt`
+ `scrapy crawl tokens -o tokens.json`
