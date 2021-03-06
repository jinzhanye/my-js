## 性能
![](https://note.youdao.com/yws/public/resource/9662a37292a46dac8f0ffbeaf116a00a/xmlnote/4D54544BBED342429264D8E4C417685D/23817)

- 浏览器a标签默认是dns预解析，<link xxx 可以对 js 控制跳转的页面做 DNS 预解析
- dns-prefetch   dns 预解析
- a标签会自动预解析，但很多浏览器对于 HTTPS页面，a标签不会预解析，所以要加<meta http....>来强制开启预解析

[缓存参考](https://yuchengkai.cn/docs/zh/frontend/performance.html#%E7%BD%91%E7%BB%9C%E7%9B%B8%E5%85%B3)


### 分类
- 网络相关
    - DNS 预解析
    - 浏览器缓存
    - 资源预加载
    - CDN
    - 使用 HTTP2
 
- 渲染过程
    - 资源懒加载

- 文件优化
    - 资源压缩
    - 图片使用雪碧图、webp
    - 服务端开启文件压缩功能

- webpack 打包优化
    - 长缓存 
    - 路由懒加载 
    - treeShaking

- 用户体验
    - loading
    - 感应热区
