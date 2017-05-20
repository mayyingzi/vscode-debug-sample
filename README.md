VSCODE Debug Guide
---

### 安装依赖

```
npm install
# or
yarn
```

### 1. 调试前端代码

1. vscode 安装 `debugger-for-chrome`
2. `npm run frontend`
3. 启动调试配置：“启动一个独立的 Chrome 以调试 frontend”
4. 在 `frontend/index.js` 中加断点
5. 访问 `http://localhost:8091/frontend/`

### 2. 调试通过 Nodemon 启动的 Node 服务器
