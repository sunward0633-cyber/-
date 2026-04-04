# OpenClash 区域绕过方案

本仓库提供一套适用于 OpenWrt + OpenClash 的“区域绕过”模板：

- `openclash-regional-bypass-template.yaml`：可直接作为 OpenClash 配置模板导入后修改的配置文件
- `openclash-ui-checklist.md`：OpenWrt / OpenClash 界面配置与核对清单

目标策略：

- 中国大陆 IP、常见国内域名、局域网与保留地址直连
- 非中国大陆流量走 VPN / 代理节点
- 国内外 DNS 分流，降低 DNS 泄漏和误分流风险

使用方式：

1. 将你的节点参数填入 `openclash-regional-bypass-template.yaml`
2. 在 OpenClash 中导入该配置
3. 按 `openclash-ui-checklist.md` 完成界面设置与核对
