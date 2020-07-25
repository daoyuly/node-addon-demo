# node c++ addon 的基本入门
- 先把demo跑起来，感性的认识下c++ addon的样子
    - 使用node-gyp构建
    ```js
    npm i -g node-gyp
    ```
    - 构建demo
    ```js
    node-gyp clean
    node-gyp configure
    node-gyp build
    /* 或者 */
    node-gyp rebuild
    ```

    - 如果都没有报错，调用下看看
    ```js
    node hello.js
    ```
- 有三套api可以使用, 可以去这里认真学习[node-addon-examples](https://github.com/daoyuly/node-addon-examples)
    - nan
    - n-api
    - node-addon-api

- binds

- 入门addon
    - [addons](https://nodejs.org/dist/latest-v8.x/docs/api/addons.html)
    - [Node.js C++ Addon应用实践](https://iweiyun.github.io/2019/01/04/node-cpp-addon/)
    - [从暴力到 NAN 再到 NAPI——Node.js 原生模块开发方式变迁](https://xcoder.in/2017/07/01/nodejs-addon-history/)

- 深入理解
    - [Node.js源码解析：深入Libuv理解事件循环](https://zhuanlan.zhihu.com/p/35039878)
