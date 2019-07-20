# found_IPpool
创建自己的IP池

国内高匿IP代理网站：https://www.xicidaili.com/nn/

先对IP代理网站进行爬虫，网站后面加上页数为请求URL，比如第12页的URL为https://www.xicidaili.com/nn/12

## 函数说明
* req_res ： 请求URL，返回字符串形式的响应
* parse_response ： 对字符串响应进行解析，提取出IP数据，并封装到pandas.DataFrame中
* verify_IP ：利用百度逐个验证IP的有效性，返回列表形式的IP池。

