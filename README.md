# border.less
解决移动端border问题，可定义任意单边框到全边框、圆角以及分割线等样式。

# 使用方法
```javascript
<style lang="less" scoped>
@import "./border.less";
...
.example {
    position: relative; //important
    height: 15px;
    .border-top();
    .border-bottom();
}
```
