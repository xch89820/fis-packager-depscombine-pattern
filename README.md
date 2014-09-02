fis-packager-depscombine
====================================

另一种打包方案，在 pack 中命中的文件，其依赖也会自动命中。

1. 安装此插件

    ```bash
    npm install fis-packager-depscombine -g
    ```
2. 启用此插件

    ```javascript
    fis.config.set('modules.packager', 'depscombine');
    ```