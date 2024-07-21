如何打包
===

```bash
cd web-next-auth
    git checkout wechat
    cd packages/next-auth
        # ubuntu 22安装pnpm: https://vsys.host/how-to/how-to-install-pnpm-on-ubuntu-22-04
        pnpm install
        pnpm run build
        pnpm pack # 将在当前目录生成next-auth-4.8.0.tgz
```