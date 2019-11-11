# 提交版本注意事项
1.　已经提交过的的正式版本不可以删除，不然会造成客户无法使用。

2.　提交的测试版本最好不要超过5个，例如：1.015,1.016.

3.　针对每一次提交的版本写好修改或者优化的内容，便于客户决定是否更新。

##使用方式

在项目的build.gradle添加：```maven { url "https://raw.githubusercontent.com/zdeps/diag/master" }```;在module的build.gradle里面添加``` api 'com.zkobd:diagso:1.015d9'```
