eletron 学习代码，最简单空项目
官方文档地址：https://electronjs.org/docs
带上了依赖库，因为发现electron安装很慢，在国内使用阿里源也很慢
使用npm run package进行打包,打包速度有点慢，不要着急，刚开始不要打包全平台的，需要打包哪个平台的就在package.json里面修改package里面的参数，指定platform参数。
electron打包可以使用electron-packager，也可以使用electron-builder，貌似electron-packager用的人比较多，资料比较容易找，但是electron-builder功能更强，打出来的包更小，源码越更安全

