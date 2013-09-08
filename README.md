# baidupan

## 关于

baidupan 是一个百度盘 API (http://pan.baidu.com) 的 Python SDK.

## 使用方法

    from baidupan.baidupan import BaiduPan

    if __name__ == "__main__":
        access_token = ''
        disk = BaiduPan(access_token)
        print disk.quota()
        print disk.upload('hello', path='/apps/appname/hello')

## release note

http://www.v2ex.com/t/81003