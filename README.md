# tokens_TokensHarness_code（更新端点兼容层）

本仓库只为改名前的 TokensHarness 旧安装（v0.3.13 及以前）保留自动更新端点：

- 旧版更新插件固定读取 `https://tokensapi.github.io/tokens_TokensHarness_code/releases.json`；
- 本仓库的定时工作流从 [TokensAPI/TokensCowork](https://github.com/TokensAPI/TokensCowork) 拉取 Release 列表并发布到 Pages；
- 旧版据此发现新的稳定版并直接从新仓库下载安装包，升级后即切换到新端点，不再依赖本仓库。

产品代码请见 [TokensAPI/TokensCowork](https://github.com/TokensAPI/TokensCowork)。
