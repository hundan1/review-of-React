0. init
   `create-react-app` （react脚手架工具） 脚手架工具的安装和使用

   > You are running `create-react-app` 4.0.1, which is behind the latest release (4.0.2).
   > We no longer support global installation of Create React App.
   > The latest instructions for creating a new app can be found here:[https://create-react-app.dev/docs/getting-started/](https://create-react-app.dev/docs/getting-started/)

   先卸载调全局工具，再安( `.` 不支持了)

   ```shell
   npm init react-app react-study
   ```

   

   改端口: package.json

   ```json
   "scripts": {
       "start": "set PORT=6789&&react-scripts start"
   }
   ```

1. hello world