# migu_music_spider
咪咕音乐歌手搜索批量下载爬虫
自动获取歌手的所有歌曲，歌词，专辑图片到同一文件夹下。

requests发送获取请求
BeautifulSoup处理返回信息
re正则匹配
json解析音乐信息
time延时功能
Pool多线程

音乐下载时，自动识别获取下一页歌曲信息；
为了避免出现重名现象，在文件名后面添加了歌曲id，作为区别，防止出错；

以后可以添加上主页歌手爬取，再进一步把歌手信息解析，获取更多歌曲信息。
json解析数据写入数据库，创建歌曲资源库。
