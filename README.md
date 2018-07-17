# DoubanSpider
python 爬虫爬取豆瓣读书信息

程序主要是由 6 个函数组成：
get_html()：请求页面，返回页面 html 源码。
get_pageurl(base_url)：从 html 源码中提取分页链接部分字段。
def bookinfo(url)：提取图书信息，以列表形式返回。
get_num(person)：判断评价人数，没有评价人数的按 10 人处理。
write2csv()：将图书信息保存为 csv 文件。
main()：程序执行的主函数。


