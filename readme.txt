做一个自动刷安卓市场下载量的程序，难点是需要变换ip以及分析各个市场的下载链接的信息

大概思路是使用httpclient模拟浏览器访问
用ip代理切换ip

代理ip地址可以从该网站抓取，需要更新以及判定是否有效
http://cn-proxy.com/

httpclient资料
http://hc.apache.org/httpcomponents-client-4.3.x/index.html