fis-packager-depscombine-pattern
====================================

基于fis-packager-depscombine打包方案
但是不同的是只分析打包规则中设置 !CB~ 标志位的项目
这样可以与其他packager一起使用，互不影响

1. 安装此插件

    ```bash
    npm install fis-packager-depscombine-pattern -g
    ```
2. 启用此插件

    ```javascript
    fis.config.set('modules.packager', 'depscombine-pattern');
    ```
3. 设置打包规则如下
   ```javascript
   '!CB~pkg/combine.js': 'main.js'
   ```
