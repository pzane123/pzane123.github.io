# Hugo Blog (Gokarna)

这个目录已经初始化为一个 Hugo 站点，并已安装/配置好 Gokarna 主题（`themes/gokarna`），同时拷贝了主题自带的 `exampleSite` 内容用于演示。

## 本地预览

```bash
hugo server -D
```

浏览器打开：`http://localhost:1313/`

## 构建静态站点

```bash
hugo --minify
```

输出目录：`public/`

## 关键配置

站点配置在 `hugo.toml`：

- `baseURL`：改成你的域名（例如 `https://blog.example.com/`）
- `title`：站点标题
- `[params]`：头像、描述、页脚、社交链接等

头像文件默认使用：`static/images/avatar.webp`

## 更新主题

主题是通过 git clone 到本地的：

```bash
git -C themes/gokarna pull
```

