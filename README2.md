# dev-sidecar
开发者边车，命名取自service-mesh的service-sidecar，意为为开发者打辅助的边车工具    
通过本地代理的方式将https请求代理到一些国内的加速通道上
    
<a href='https://gitee.com/docmirror/dev-sidecar'><img src='https://gitee.com/docmirror/dev-sidecar/badge/star.svg?theme=dark' alt='star'/></a>
<a href='https://github.com/docmirror/dev-sidecar'><img alt="GitHub stars" src="https://img.shields.io/github/stars/docmirror/dev-sidecar?logo=github"></a>


## 特性

### 1、 dns优选（解决国内dns污染问题）
* 根据网络状况智能解析最佳域名ip地址，获取最佳网络速度
* 解决一些网站和库无法访问或访问速度慢的问题
* 建议遇到打开比较慢的国外网站，可以优先尝试将该域名添加到dns设置中（注意：被GFW封杀的无效）     
