# Chain Alpha GMGN 插件

这是 Chain Alpha 的公开 Chrome 插件包，用于在 GMGN 代币页面显示 CA 分析面板和底部异动数据。

## 下载

进入最新 Release 页面下载：

- `gmgn_ca_clusters.zip`

Release 地址：

https://github.com/CelestialBlossoms/chain-alpha-gmgn-plugin/releases

## 安装方式

1. 下载 `gmgn_ca_clusters.zip`。
2. 解压这个压缩包。
3. 打开 Chrome 浏览器，进入 `chrome://extensions`。
4. 打开右上角的“开发者模式”。
5. 点击“加载已解压的扩展程序”。
6. 选择刚才解压出来的插件文件夹。
7. 打开 GMGN 的代币详情页面，页面右侧会显示 Chain Alpha 分析面板。

## 使用说明

- 插件只在 `gmgn.ai` 的代币页面生效。
- 打开 GMGN 代币页面后，插件会自动识别当前 CA。
- 点击面板里的“点击复制CA”可以复制当前代币 CA。
- 面板会显示 CA 分析、分类摘要、底部异动列表、池子/市值比值等数据。
- 如果代币存在重点底部观察标记，插件会用醒目的边框和标签提示。

## 升级方式

1. 下载新的 `gmgn_ca_clusters.zip`。
2. 删除旧的解压目录，重新解压新包。
3. 回到 `chrome://extensions`。
4. 找到 Chain Alpha 插件，点击刷新按钮。
5. 刷新 GMGN 页面。

## 常见问题

- 如果 GMGN 页面没有显示面板，先确认当前页面是 GMGN 代币详情页，然后刷新页面。
- 如果刚升级后还是旧显示，回到 `chrome://extensions` 点击插件卡片上的刷新按钮。
- 如果面板显示接口异常，说明插件无法访问 Chain Alpha API 服务，需要等待服务恢复或检查网络。
- 如果 Chrome 提示不能安装压缩包，需要先解压，再使用“加载已解压的扩展程序”。

## 文件说明

- `gmgn_ca_clusters.zip`：已经打包好的 Chrome 插件。
- `extension/`：未压缩的插件源码目录，可以直接在 Chrome 中加载。
