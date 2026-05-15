# Chain Alpha GMGN CA Clusters

这是 Manifest V3 Chrome 插件，用于在 GMGN 代币页面展示 Chain Alpha 的 CA 分析结果。

## 本地加载

1. 打开 Chrome 浏览器。
2. 进入 `chrome://extensions`。
3. 打开“开发者模式”。
4. 点击“加载已解压的扩展程序”。
5. 选择当前 `extension` 文件夹。
6. 打开 GMGN 代币详情页面。

## 功能说明

- 自动识别 GMGN 页面里的代币 CA。
- 显示分类摘要、钱包结构、底部筹码观察、历史异动涨幅等分析信息。
- 显示流动性和市值的比值，并按区间标注状态。
- 支持点击复制 CA。
- 支持展示底部异动列表。

## 注意事项

- 插件需要访问配置好的 Chain Alpha API 服务。
- 修改插件文件后，需要回到 `chrome://extensions` 手动刷新插件。
- 如果页面没有出现面板，刷新 GMGN 页面或重新加载插件。
- 如果接口暂时没有数据，面板会显示对应的空状态或错误提示。
