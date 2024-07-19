# ShokaX Can
## 开始
ShokaX 即食罐头，使用 pnpm 加热即可食用，执行下列命令：
```bash
git clone https://github.com/theme-shoka-x/shokax-can --depth=1
cd shokax-can
pnpm install
hexo s # 如果报错更换为 pnpm dlx hexo s
```

当前内容物版本：ShokaX v0.4.11 不含 lightning-minify

## 创建链接
```bash
mklink /J .\themes\shokax .\node_modules\hexo-theme-shokax # windows CMD
# 或
cd ../themes && ln -s ../node_modules/hexo-theme-shokax shokax # Linux Bash
```
随后可以通过`themes/shokax`访问主题文件