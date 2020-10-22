# Every Utils JS

> **ES5 规范的的 Javascript 工具类**  
> 须知：该项目起源于大学期间一个项目所用到的方法，后续的更新仅针对于已有的 bug 修复。

包含 Array, Function, Object 等等工具方法，具体见源代码

## 使用方法

### HTML
1. 下载源码通过 script 标签引入
2. 使用：
    ```javascript
       var eUtils = window.eUtils;
       // ...
    ```
### NodeJS
1. 下载源码或通过 NPM 引入  
    NPM 引入： `npm i @palerock/every-utils`
2. 使用：
    ```javascript
       var eUtils = require('@palerock/every-utils');
       // ...
    ```

### 方法的调用
1. 直接调用不重名的方法
    ```javascript
        eUtils.isArray([]) // true
    ```
2. 通过具体 Utils 模块调用
    ```javascript
        eUtils.BaseUtils.isArray([]) // true
    ```
   
> 具体 Utils 模块以及相关方法参见源码及注释

## 相关地址
- 主页：[https://palerock.cn/projects]()
- Github (优先更新源码)：[https://palerock.cn/projects]()
- Gitee：[https://palerock.cn/projects]()
## 欢迎其它贡献者的加入或提出疑问或建议