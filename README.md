这是通过Scrapy创建的的爬虫项目，用于学习爬虫

## 新建项目

在终端运行`scrapy startproject sp1`

## 创建爬虫

进入创建的项目目录，`cd sp1`
执行创建爬虫的命令：`scrapy genspider baidu baidu.com`

## 修改配置文件

`ROBOTSTXT_OBEY = False`

## 修改Spyders中的脚本

```py
def parse(self, response):
        print(response.text)
```

## 运行爬虫

`scrapy crawl baidu`
`scrapy crawl baidu --nolog` 不显示日志



