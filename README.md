# vite-azure

[vitejs](https://cn.vitejs.dev/guide/#overview)

```js
# yarn
yarn create @vitejs/app my-vue-app --template vue
```

## azure

執行階段堆疊 `Node 12 LTS` 作業系統 `Linux`

[vite-azure](https://portal.azure.com/#@git4u.net/resource/subscriptions/35a5d675-e55d-42f4-b870-6edfec306d93/resourcegroups/vite-azure/providers/Microsoft.Web/sites/vite-azure/appServices)

Settings > secrets Name: `AZURE_WEBAPP_PUBLISH_PROFILE`
portal.azure > 概觀 取得發行設定檔 -> secrets Value: `vite-azure.PublishSettings Value`

App Service FAIL

> npm WARN notsup Unsupported engine for vite@2.3.6: wanted: {"node":">=12.0.0"} (current: {"node":"10.24.1","npm":"6.14.12"})

## Azure Static Web Apps

 Learn > 瀏覽 > [Azure Static Web Apps](https://docs.microsoft.com/zh-tw/learn/paths/azure-static-web-apps/)  
[使用 Node.js 在 Azure 上建立新的靜態 Web 應用程式](https://docs.microsoft.com/zh-tw/azure/developer/javascript/how-to/create-static-web-app)  
[快速入門：在 Azure 入口網站中建立您的第一個靜態網站](https://docs.microsoft.com/zh-tw/azure/static-web-apps/get-started-portal?tabs=vue)

## 驗證 Build 後所建立的檔案

npm [serve](https://www.npmjs.com/package/serve)  
安裝 serve 套件 
於 Terminal 中輸入 `npm install -g serve`  

驗證 Build 後所建立的檔案  
於 Terminal 中輸入 `serve -s dist`

http://localhost:5000/

## Visual Studio Code

[Azure Static Web Apps](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps) for Visual Studio Code

[建立靜態 Web 應用程式](https://docs.microsoft.com/zh-tw/learn/modules/publish-app-service-static-web-app-api/4-exercise-static-web-apps?pivots=vue)

`git push`