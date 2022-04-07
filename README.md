# data-waster-dummy
流量消失器源码
CentOS使用方法
（80端口被占用时，可修改httpd默认端口，再重启httpd # sed -i 's/Listen 80/Listen 81/g' /etc/httpd/conf/httpd.conf && systemctl restart httpd）
# yum install httpd -y && systemctl start httpd && systemctl enable httpd
# cd /var/www/html 
# wget https://ghproxy.com/https://raw.githubusercontent.com/cduang/data-waster-dummy/main/html/index.html
# wget https://ghproxy.com/https://raw.githubusercontent.com/cduang/data-waster-dummy/main/html/data-waster-dummy2.gif
访问http://服务器ip/即可
![TIM截图20220408020406](https://user-images.githubusercontent.com/42569425/162268069-9fa307f4-4621-47c6-a59f-ba1f3677d27d.png)
