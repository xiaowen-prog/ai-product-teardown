# AI 产品拆解与竞品分析 Skill

通过真实任务取证、效果评测、人机分工、模型成本与产品壁垒分析，形成有证据、可复核的产品研究报告。

## 使用方法

本仓库是 AI Agent Skill，不是独立应用。将仓库作为一个技能文件夹放入支持 `SKILL.md` 的 Agent 的技能目录，或让 Agent 读取 [SKILL.md](SKILL.md) 后执行任务。具体加载方式以所用 Agent 为准。

```text
使用 $ai-product-teardown，分析这款产品及其主要替代方案：[产品链接]。输出 Markdown 报告。
```

## 文件结构

- `SKILL.md`：七步拆解工作流与交付要求。
- `references/evidence.md`：取证、来源核查与二次验证。
- `references/analysis.md`：评测、人机分工、技术机制与成本。
- `references/report.md`：报告结构、图表与交付检查。
- `agents/openai.yaml`：支持该格式的 Agent 的界面元数据。

浏览、实测及飞书交付需要运行环境具备相应工具与权限；没有能力时应说明限制，不编造测试结果。方法来源见 SKILL.md；原始案例、账号、截图和非公开材料不随仓库提供。

## 开源许可

[MIT License](LICENSE)。第三方产品、来源及链接的权利归各自权利人所有。
