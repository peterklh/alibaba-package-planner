# 阿里国际站营销保效方案清单(静态页)

交互式方案清单页面:方案计算器、星级匹配、权益对比、AWB 版本对比。

## 文件说明

- `index.html` — 部署文件(必须命名为 index.html,GitHub Pages 才能直接访问根目录)

## 部署步骤

### 方式一:网页上传(无需安装任何工具)

1. 打开仓库页面(如 `https://github.com/你的用户名/仓库名`)
2. 点击 **Add file → Upload files**
3. 把本文件夹中的 **index.html** 拖拽上传
4. 点击 **Commit changes**
5. 仓库页 → **Settings → Pages**
6. Source 选择 **"Deploy from a branch"** → Branch: **main**, folder: **/ (root)** → **Save**
7. 等待 1-2 分钟,访问 `https://你的用户名.github.io/仓库名/`

### 方式二:命令行推送(需配置 git)

```bash
git clone https://github.com/你的用户名/仓库名.git
cd 仓库名
cp /本文件夹路径/index.html .
git add index.html
git commit -m "deploy: 更新方案清单页面"
git push
```

推送后同样在 Settings → Pages 开启即可。

## 备注

- 页面为纯静态单文件,无外部依赖,离线可用
- 国内网络访问 github.io 可能不稳定,如需国内加速可改用 Gitee Pages 或阿里云 OSS
