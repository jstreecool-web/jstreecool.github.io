# AI Data Centre Site Selector · AI数据中心选址决策系统

Interactive tools that score candidate markets for AI data centres on power, connectivity, market demand, cost and risk, for three workloads: AI training, AI inference and SME private deployment. Both editions use the same model, and each page works in English and Chinese.

交互式工具，按电力、网络连接、市场需求、成本和风险，为AI训练、AI推理和中小企业私有部署三类业务给候选市场打分。两个版本使用同一套模型，均支持中英文切换。

| Edition 版本 | Markets 市场 | Link 链接 |
|---|---|---|
| Europe 欧洲 | 27 | [jstreecool-web.github.io/jstreecool.github.io](https://jstreecool-web.github.io/jstreecool.github.io/) |
| China & Hong Kong 中国内地与香港 | 15 | [china.html](https://jstreecool-web.github.io/jstreecool.github.io/china.html) |

## How it works 工作原理

- Each criterion is scored 0–100 relative to the other markets, then weighted. Choose a workload scenario or a preset (Investor, Developer, cross-border cloud vendor) or set the weights yourself.
- A 10-year total cost of ownership model covers build, land, energy and other opex for the project size you set.
- 400 simulations vary published figures by ±5% and estimates by ±15% to give each score a range.
- A Go / No-Go rule flags markets whose time to power exceeds your limit or that carry a high risk rating.

- 每项准则按相对其他市场的0–100分计分后加权；可选择业务场景、预设权重（投资方、开发方、跨境云厂商），也可自行调整。
- 10年总拥有成本模型涵盖建设、土地、能源和其他运营成本。
- 400次模拟：公开数据浮动±5%，估算值浮动±15%，给出得分区间。
- 可行/否决规则：获电或并网时间超过上限、或风险评级过高的市场会被标记。

## Data 数据

All data is a snapshot as of November 2026. Figures marked ≈ are estimates; every source is listed in each page's “Sources and gaps” tab. Replace estimates with broker, grid or approval data before relying on a ranking.

数据为2026年11月的快照。标 ≈ 的是估算值，所有来源见各页面的“数据来源与缺口”标签页。依据排名做决策前，请用经纪机构、电网或审批部门的数据替换估算值。

The China & Hong Kong base map shows coastlines only and is not an approved standard map. 中国内地与香港版底图只绘制海岸线，不是审定的标准地图。

## Licence 许可

© 2026 jstreecool. Analysis and code under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/); see `LICENSE`. Third-party data stays under its publishers' terms.

分析与代码采用 CC BY-NC 4.0 许可，详见 `LICENSE`。第三方数据仍适用其发布方条款。
