����ͨ��Scrapy�����ĵ�������Ŀ������ѧϰ����

### �½���Ŀ

���ն�����`scrapy startproject sp1`

### ��������

���봴������ĿĿ¼��`cd sp1`
ִ�д�����������`scrapy genspider baidu baidu.com`

### �޸������ļ�

`ROBOTSTXT_OBEY = False`

### �޸�Spyders�еĽű�

```py
def parse(self, response):
        print(response.text)
```

### ��������

`scrapy crawl baidu`
`scrapy crawl baidu --nolog` ����ʾ��־



