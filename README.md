# ha-airx
airx的home assistant插件



需要在configuration.yaml中开启packages
```yaml
homeassistant:
  packages: !include_dir_named packages
```




需要自己根据自己的情况修改airx.yaml和secrets.yaml
获取自己的token、userid、deviceid办法
https://bbs.hassbian.com/thread-2113-1-1.html

```yaml
airx_token: 0000000000000
airx_user_id: 111111
airx_device_id: 22222
airx_device2_id: 22222
```


效果

![https://wx3.sinaimg.cn/large/56e89fd7ly1fowbf9pxoej20f00cgdgc.jpg](https://wx3.sinaimg.cn/large/56e89fd7ly1fowbf9pxoej20f00cgdgc.jpg)

![https://wx1.sinaimg.cn/large/56e89fd7ly1fowcecd4vfj20ip0m6jsg.jpg](https://wx1.sinaimg.cn/large/56e89fd7ly1fowcecd4vfj20ip0m6jsg.jpg)
