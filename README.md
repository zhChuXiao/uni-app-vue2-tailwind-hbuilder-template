# uni-app-vue2-tailwind-hbuilder-template

这是一个使用 `hbuilderx` + `uni-app` + `vue2` + `tailwind` 构建的小程序模板。可以直接在 `hbuilderx` 中导入运行。

## 使用方式

先在项目目录下，执行 `yarn` 进行安装，然后在 `hbuilderx` 中打开项目，进行运行和发布。

## 注意

在项目里面添加目录，在里面写 `.vue` 文件的时候，记得更新 `tailwind.config.js` 的 `content` 数组，把新的目录包裹进去。不然 `tailwindcss` 是不会生成添加的目录里面的 `class` 的！

比如你添加一个 `components` 文件夹，你就在 `content` 加入 `resolve("./components/**/*.{vue,js,ts,jsx,tsx,wxml}"),`, 小程序分包同理。

## HbuilderX 智能提示工具

DCloud-HBuilderX团队提供了对应的插件，可以去

<https://ext.dcloud.net.cn/plugin?id=8560> 进行下载，即可产生智能提示。

## Related projects

### 插件核心

[weapp-tailwindcss-webpack-plugin](https://github.com/sonofmagic/weapp-tailwindcss-webpack-plugin) 提供转义功能，欢迎 `fork`/`star`

### CLI 工具

[weapp-ide-cli](https://github.com/sonofmagic/utils/tree/main/packages/weapp-ide-cli): 一个微信开发者工具命令行，快速方便的直接启动 ide 进行登录，开发，预览，上传代码等等功能。

### 模板 template

[uni-app-vite-vue3-tailwind-vscode-template](https://github.com/sonofmagic/uni-app-vite-vue3-tailwind-vscode-template)

[uni-app-vue3-tailwind-vscode-template](https://github.com/sonofmagic/uni-app-vue3-tailwind-vscode-template)

[uni-app-vue2-tailwind-vscode-template](https://github.com/sonofmagic/uni-app-vue2-tailwind-vscode-template)

[weapp-native-mina-tailwindcss-template](https://github.com/sonofmagic/weapp-native-mina-tailwindcss-template)

### 预设 tailwindcss preset

[tailwindcss-miniprogram-preset](https://github.com/sonofmagic/tailwindcss-miniprogram-preset)

