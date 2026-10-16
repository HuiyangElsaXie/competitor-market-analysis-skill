# Competitor and Market Analysis / 竞品与市场分析

Start with the [LanternDesk synthetic comparison](examples/fictional-example.md): supplied briefs → comparable matrix → source ledger → qualified recommendation. [Blank brief](references/output-template.md) · [Skill entry](SKILL.md). / 先看合成竞品矩阵与建议。

## English
A personal-use marketing workflow skill to compare alternatives and develop evidence-led positioning hypotheses. This skill is continuously updated as practical learning develops; no release schedule, maintenance commitment, or research outcome is guaranteed. This is a lightweight first version, not a production research platform.

### Use
Give an AI agent SKILL.md and a short business brief: product, audience, market, decision, and any existing evidence. Example request: “Use this skill to compare the supplied scheduling alternatives for solo tutors. Align currency, billing unit and plan limits, mark unknown features, and recommend one positioning question to investigate.” Return a comparable landscape, dated source ledger, qualified positioning hypothesis, counterevidence and the next verification step. The skill itself grants no account access. Public web or connected read-only tools are optional; supplied-material analysis works offline with limitations disclosed.

### Contents
- SKILL.md: agent workflow and evidence safeguards
- references/output-template.md: reusable deliverable structure
- examples/fictional-example.md: clearly synthetic demonstration, never actual research
- THIRD_PARTY_NOTICES.md and licenses/: verified upstream source and retained license

### Attribution and boundaries
Adapted from [ishwarjha/claude-marketing-research-skill](https://github.com/ishwarjha/claude-marketing-research-skill/tree/0b31cbde9a51c4a0a1d2ceca68fd39db00f5c558) for task fit, not popularity. See THIRD_PARTY_NOTICES.md for exact scope and rights. No repository-wide license has been selected for original contributions. Upstream material retains its applicable license; this does not change those rights. No scripts, paid services, automatic credentials, publication, or hidden integrations are included. Validation is structural review plus a fictional walkthrough, not live effectiveness testing.

## 中文
这是个人使用的营销工作流技能，用于比较替代方案，形成有证据依据的定位假设。项目会随实践持续更新，但不承诺固定更新频率、维护服务或研究效果。目前是轻量首版。

示例请求：“请用 [SKILL.md](SKILL.md) 比较我提供的导师排课替代方案，核对计费单位、币种与限制，未知功能不要判为缺失。”交付可比矩阵、带日期来源台账、定位假设、反证和下一步核验。先复用获准上下文，只追问关键缺口；没有浏览工具就说明仅分析已给资料。

输出模板在 references/；examples/ 中全部为虚构演示，不是真实案例。真实观察、分析推断和待验证假设必须分开。不会自动安装集成、读取凭据、联系客户、付费调研或发布内容。

上游模块采用 Apache-2.0；来源、固定提交、修改说明和完整许可文本已保留。原创部分尚未选择仓库级许可证。质量检查限于结构与虚构走读，不代表真实营销成效已验证。
