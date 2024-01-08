
# i茅台预约工具----GitHub Actions版

### 原理：
```shell
1、登录获取验证码
2、输入验证码获取TOKEN
3、获取当日SESSION ID
4、根据配置文件预约CONFIG文件中，所在城市的i茅台商品
```


### 使用方法：

### 1、安装依赖
```shell
pip3 install --no-cache-dir -r requirements.txt
```

### 2、修改config.py，按照你的需求修改相关配置，这里很重要，建议每个配置项都详细阅读。


### 3、按提示输入 预约位置、手机号、验证码 等，生成的token等。很长时间不再需要登录。支持多账号，支持加密。





