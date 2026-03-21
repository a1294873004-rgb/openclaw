openkey:
sk-36d663d7a7714f7fb01ec8bc6f621bbf


# 1. 克隆并构建
git clone https://github.com/openclaw/openclaw.git
cd openclaw
pnpm install
pnpm ui:build
pnpm build

# 2. 全局链接 CLI
pnpm link --global
# 或者跳过链接，在仓库内使用 pnpm openclaw ...

# 3. 运行配置向导
openclaw onboard --install-daemon
