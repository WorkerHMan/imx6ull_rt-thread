# imx6ull/rt-thread

RT-Thread Smart 内核（rt-smart），i.MX6ULL 板级 BSP 改动在此

## 用途

这是 Gerrit 上的项目仓库，评审流程：

```bash
git clone ssh://guoqiangh@localhost:29418/imx6ull/rt-thread
cd rt-thread
curl -sS -o .git/hooks/commit-msg http://localhost:8080/tools/hooks/commit-msg
chmod +x .git/hooks/commit-msg

git commit -am "feat: xxx"
git push origin HEAD:refs/for/main
```

详见 `imx6ull/product` 里的 `01_docs/20-Gerrit评审服务器.md`。
