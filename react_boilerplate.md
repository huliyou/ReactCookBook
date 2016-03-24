# React_ boilerplate

我自己搭建了一个react boilerplate，帮助新手能快速开始React项目

项目地址：[react-boilerplate](https://github.com/huliyou/react-boilerplate)

之后我会把这个项目做成npm cli，完成项目初始化、开发、调试、测试、构建、发布。

```
.
├── README.md
├── dis                     # The folder for compiled output
│   └── index.html
├── node_modules            # 3rd-party libraries and utilities
├── package.json            # The list of 3rd party libraries and utilities
├── src                     # The source code of the application
│   ├── AppInfo.json        # app info config
│   ├── actions             # Action creators that allow to trigger a dispatch to stores
│   ├── asset               # the resource of css, images
│   ├── component           # React components
│   ├── container           # combine components
│   ├── index.html          # web entry file
│   ├── index.js            # app entry file
│   └── reducers            # deal with actions and refrash store
├── test                    # unit test
│   ├── actions
│   ├── components
│   ├── reducers
│   └── test_helper.js
├── webpack.config.dev.js   # webpack dev config
└── webpack.config.prod.js  # webpack prod config
```