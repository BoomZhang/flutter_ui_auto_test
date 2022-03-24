（Android&iOS）UI自动化框架中，为混合型或纯flutter UI自动化提供便捷的能力。
详细原理可参考：[Flutter UI测试自动化原理与实践](https://mp.weixin.qq.com/s/htimPf_vt94i4Oz8H9_MQQ)

## 环境：
python环境：python3
XX：

## 快速使用
### python侧：
安装依赖：pip install -r requirements.txt <br>

1. 连接设备：<br>`fd = fd.connect('ip')`
2. 根据ID获取元素操作点击：<br>`fd.click_id_by_position(element_id='XXX', logtext='点击')`
3.  根据ID直接点击<br> `fd.click_id('XX')`
4.  输入文字<br>`fd.set_text('XXX', '123')`
5. 断言<br>`fd.assert_toast('保存成功')`
6. 关闭<br>`fd.__close__()`
    

> 上层操作API在python/下，可独立与客户端的flutter侧建立链接。与在原生UI自动化框架混合，需要要保持FlutterDirver持续建立链接。

### dart侧：

## 代码导读


## 联系方式

