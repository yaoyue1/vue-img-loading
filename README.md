vue-img-loading 是一个图片下载的loading组件

# 快速开始

```html
    <VueImgLoading :imgs="imgs" @done="done" @progress="progress"></VueImgLoading>
```

### props
 |属性 | 说明 | 类型 | 默认值 |
 |---  | --- | ---  | --- |
 |imgs  | 需要预加载的图片数组  | Array | 无  |

### Event
 |事件 | 说明 | 类型 | 默认值 |
 |---  | --- | ---  | --- |
 | progress |  预加载过程 | function | down(已下载的张数) ， total(图片总张数) |
 |done  |  预加载完成 | function |   |