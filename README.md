# React 18 with Webpack and TypeScript

這是一個基本的 React 18 專案配置，使用了 Webpack 和 TypeScript，並包括以下功能：

- React 18
- Webpack 5
- TypeScript
- Sass
- Jest 和 React Testing Library 進行測試
- ESLint 進行程式碼檢查和格式化

## 開始使用

1. 複製或下載原始碼。
2. 在終端中將目錄更改為包含您的腳本的目錄。
3. 給腳本添加可執行權限，使用以下命令：`chmod +x create-react-starter.sh`。
4. 執行腳本，使用以下命令：`./create-react-starter.sh projectName`。
5. 會自動安裝react
6. 打開瀏覽器並導航到 `http://localhost:4800` 查看應用程式運行情況。

## 可用指令

在專案目錄中，可以執行以下指令：

### `yarn start`

啟動開發伺服器，在 `http://localhost:4800`。

### `yarn build`

將應用程式構建為生產環境所需的文件，並輸出到 `dist` 資料夾。

### `yarn test`

使用 Jest 執行測試。

### `yarn lint`

運行 ESLint 檢查程式碼品質問題。

## 專案結構

專案的結構如下：

```
├── dist                   # 構建輸出資料夾
├── node_modules
├── src
│   ├── __test__           # 測試檔案資料夾
│   ├── App.tsx            # 主要的 App 元件
│   ├── index.html         # HTML 模板檔案
│   ├── index.tsx          # 入口檔案
│   ├── styles.scss        # Sass 樣式
│   └── ...                # 其他元件和檔案
├── .eslintrc.json         # ESLint 設定檔案
├── jest.config.js         # Jest 設定檔案
├── package.json
├── tsconfig.json          # TypeScript 設定檔案
└── webpack.config.js      # Webpack 設定檔案
```

## 授權

該專案使用 MIT 授權。