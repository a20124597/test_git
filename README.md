# KMS client
Horizon Robotics Key Management System Python SDK.
## 使用
### 库依赖包
pip install requests
### 接口
#### 获取秘钥
函数：hobot_kms_get_key()
#### 秘钥签名
函数: hobot_kms_sign(signInfo)
signInfo输入需要签名的字符串
### 引入包方法
#### 1.拷贝文件
将kmspythonsdk包直接拷入需要导入的项目目录下
#### 2.导入python库
cd py_sdk
python setup.py bdist_egg 即可打包一个kmspysdk的包
python setup.py install   安装包
需要使用直接import kmspythonsdk
## 文档
- 项目用户手册Wiki: [KMS用户手册](http://wiki.hobot.cc/pages/viewpage.action?pageId=69333771)
- 项目设计文档Wiki: [KMS详细方案设计](http://wiki.hobot.cc/pages/viewpage.action?pageId=68769249)

## 支持
如需使用支持，可联系地平线机器人平台与技术部云平台部 KMS项目团队
