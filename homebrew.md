## 安装homebrew
- 443 问题：`curl: (7) Failed to connect to raw.githubusercontent.com port 443: Connection refused error` 一般是因为DNS污染，解决方案：
  打开 https://www.ipaddress.com/ 输入访问不了的域名，查询到正确的IP，查询之后可以获得正确的 IP 地址，在本机的 host 文件中添加，建议使用 [switchhosts](https://github.com/oldj/SwitchHosts/releases) 方便 host 管理.
- 更新过慢问题：这篇[文章](git@github.com:motherMaker/docs.git)比较靠谱
