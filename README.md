1、安装  gitkraken，会自动安装到 C 盘，到C:\Users\{用户名}\AppData\Local\gitkraken 目录，找到gitkraken.exe 自行创建快捷方式；

2、安装 Node.js >= 12，https://nodejs.org/zh-cn；

3、安装 yarn
   npm install --global yarn
   
4、关闭 gitkraken，进入 something_interesting 根目录，执行：
   yarn install
   yarn build
   yarn gitcraken patcher

5、如果 yarn gitcraken patcher 命令报错，则尝试
   gitcracken patcher --asar ~/Downloads/gitkraken/resources/app.asar #将 app.asar 文件的路径填写正确
      或者在 /dist/src/patcher.js 中添加 app.asar 文件的搜索路径


6、屏蔽更新，在 hosts 文件中添加:
   0.0.0.0 release.gitkraken.com

