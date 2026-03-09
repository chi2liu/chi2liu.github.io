---
layout: page
title: 开源贡献
permalink: /opensource/
---

<div style="text-align:right; margin-bottom: 10px;">
<a href="{{ site.baseurl }}/opensource-en">English</a> | 中文
</div>

以下是对各开源项目的贡献详情，涵盖 MCP 框架、智能体框架、大模型推理引擎以及强化学习训练框架等方向。

<div style="overflow-x: auto;">
<table>
<thead>
<tr>
<th>类别</th>
<th>框架</th>
<th>PR #</th>
<th>贡献摘要</th>
<th>影响</th>
</tr>
</thead>
<tbody>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1321">#1321</a></td>
<td>OpenAPI 性能优化</td>
<td>~34% 性能提升</td>
</tr>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1322">#1322</a></td>
<td>字符串操作优化</td>
<td>降低延迟与 CPU 开销</td>
</tr>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1342">#1342</a></td>
<td>类型注解改进</td>
<td>提升类型安全性与可维护性</td>
</tr>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1405">#1405</a></td>
<td>错误处理标准化</td>
<td>更健壮一致的错误处理</td>
</tr>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1425">#1425</a></td>
<td>AllOf 处理改进</td>
<td>提升 Schema 兼容性</td>
</tr>
<tr>
<td>MCP</td>
<td>FastMCP</td>
<td><a href="https://github.com/ilowin/fastmcp/pull/1395">#1395</a></td>
<td>utilities/components 模块全面测试</td>
<td>提升测试覆盖率与可靠性</td>
</tr>
<tr>
<td>智能体框架</td>
<td>CrewAI</td>
<td><a href="https://github.com/crewAIInc/crewAI/pull/3251">#3251</a></td>
<td>字符串操作性能优化</td>
<td>提升运行时效率</td>
</tr>
<tr>
<td>智能体框架</td>
<td>CrewAI</td>
<td><a href="https://github.com/crewAIInc/crewAI/pull/3255">#3255</a></td>
<td>LLM 消息格式改进</td>
<td>更好的消息一致性与解析</td>
</tr>
<tr>
<td>大模型推理引擎</td>
<td>vLLM</td>
<td><a href="https://github.com/vllm-project/vllm/pull/21917">#21917</a></td>
<td>调度器快速路径请求移除优化</td>
<td>~18.7% 性能提升</td>
</tr>
<tr>
<td>大模型推理引擎</td>
<td>vLLM</td>
<td><a href="https://github.com/vllm-project/vllm/pull/22782">#22782</a></td>
<td>LoRA 配置文档改进</td>
<td>更清晰的使用指南与性能提示</td>
</tr>
<tr>
<td>大模型推理引擎</td>
<td>vLLM</td>
<td><a href="https://github.com/vllm-project/vllm/pull/21816">#21816</a></td>
<td>修复 Scheduler 混合请求 ID 比较 TypeError</td>
<td>关键正确性 Bug 修复</td>
</tr>
<tr>
<td>大模型推理引擎</td>
<td>SGLang</td>
<td><a href="https://github.com/sgl-project/sglang/pull/8973">#8973</a></td>
<td>Chunked prefill 验证 Bug 修复</td>
<td>支持稳定生产环境部署</td>
</tr>
<tr>
<td>SFT & RL</td>
<td>Hugging Face TRL</td>
<td><a href="https://github.com/huggingface/trl/pull/3874">#3874</a></td>
<td>GRPO reward 处理验证修复</td>
<td>强化学习训练正确性修复</td>
</tr>
<tr>
<td>SFT & RL</td>
<td>Hugging Face TRL</td>
<td><a href="https://github.com/huggingface/trl/pull/3875">#3875</a></td>
<td>Truncate 向量化操作优化</td>
<td>性能提升</td>
</tr>
<tr>
<td>SFT & RL</td>
<td>Hugging Face TRL</td>
<td><a href="https://github.com/huggingface/trl/pull/3876">#3876</a></td>
<td>Completion IDs 列表转换优化</td>
<td>降低 Pipeline 开销</td>
</tr>
<tr>
<td>SFT & RL</td>
<td>Verl</td>
<td><a href="https://github.com/volcengine/verl/pull/2827">#2827</a></td>
<td>GPU 设备放置修复</td>
<td>~6.5× 加速；修复关键 GRPO/GPG/RLOO/OPO Bug</td>
</tr>
</tbody>
</table>
</div>
