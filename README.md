# solution_mock_api

## 域名
> http://test-09.videojj.com/

## 获取节目列表
> GET   /menu

| 参数 | 备注 |
| ------------- | ------------- |
| keyword | 搜索关键字 |
| type | 分类id |
| pn | 第几页，从0开始计数 |
| ps | 一页显示数量 |

## 获取分类列表
> GET   /types

## 获取视频评论列表
> GET   /comments

| 参数 | 备注 |
| ------------- | ------------- |
| menuId | 节目id |
| pn | 第几页，从0开始计数 |
| ps | 一页显示数量 |