# pjsk_sticker

> 啤酒烧烤角色贴纸生成插件

## 指令列表

|指令|描述|示例|
|---|---|---|
|help pjsk贴纸|获取全部指令帮助|[]为必填参数
|pss `[角色名]` `[贴纸编号]` `[任意文本]`|自定义贴纸，参数空格分割|pss 1 1 测试文本|
|pss别名 `[角色名]`|获取角色别名，返回内容可用于`[角色名]`|pss别名 1|
|pss角色 `[角色名]`|获取角色贴纸详情,返回内容可用于`[贴纸编号]`|pss角色 1|
|pss列表|获取所有角色默认名称|pss列表

## TODO

- [x] 敏感词过滤
- [ ] 数据库管理
- [ ] 坐标自定义