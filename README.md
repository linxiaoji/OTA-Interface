OTA-Interface
===================

## [点击此处观看演示视频](http://www.bilibili.com/video/av3834711/)

## OTA 更新器使用文档



### 0x01


   **第一步**
```
    在build.prop添加以下代码
    
    ro.rom.device.name=
    ro.rom.brand.name=
    ro.rom.author=
    ro.rom.type=
```
   
   
   **第二步**
```   
    根据自己的机型及系统在刚刚添加的代码后加上相应代码
   
    例如：
    ro.rom.device.name=8675-A
    ro.rom.brand.name=Coolpad
    ro.rom.author=Yuwen
    ro.rom.type=CM-12.1
    
    (注:ro.rom.type这行可以根据相应系统填EMUI-3.1/Flyme-4.5/MIUI-7.1)
```      
   **第三步**
```   
    重启手机使build.prop生效
```      
   **第四步**
```   
    使用ROM上传APP上传ROM信息
```      
   **第五步**
```   
    打开OTA更新器即可检查更新成功
```      
   **第六步**
```   
    上传 ROM 包到网盘,在当前数据条目中加入网盘链接即可推送给用户
```   
   
### 0x02
```
    ROM 数据上传的 APP 已经发布，在 build.prop 加入数据并重启后打开 APP 注册用户,
    请联系作者 QQ：294958213 开放用户权限,上传成功后会显示一个 ROM ID ,
    此 ID 对应一个 ROM 具有唯一性,也是识别 ROM 的唯一凭据,一定程度上防止盗包的产生，
    如果给予 ROM 发布器 ROOT 权限,那么可以自动写入 ROM ID 到 build.prop 并且无需重启,
    如果不给予 ROM 发布器 ROOT 权限,那么请把 ROM ID 手动加入 buil.prop 后重启,即可生效,
    上传 ROM 到论坛后可以把论坛链接,或者网盘链接给我,录入数据库,同时如果有更新日志也可以发给我
```

### 0x03

###想要功能更强大的 OTA 吗,那么请捐助我
![](https://github.com/Omico/OTA-Interface/blob/master/DonationMe.png)
     
