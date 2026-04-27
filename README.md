# Supabase 中文汉化插件

将 Supabase Dashboard 的英文界面汉化为中文的浏览器油猴脚本。

## 安装

1. 安装浏览器插件 [Tampermonkey](https://www.tampermonkey.net/)（推荐）或 Violentmonkey
2. 点击 Tampermonkey 图标 → **添加新脚本**
3. 将 [supabase-cn.js](./supabase-cn.js) 的内容完整粘贴进去，保存即可

## 覆盖范围

- 项目列表、项目概览、连接配置
- 团队管理、邀请成员、组织设置
- 数据库：表编辑器、SQL 编辑器、函数、触发器、索引、策略、角色等
- 身份认证：提供商、用户会话、速率限制、MFA、邮件配置
- 存储：存储桶、S3 配置、向量存储
- 边缘函数：部署、模板、密钥管理
- 实时服务：频道、广播、在线状态
- 日志与分析、顾问、可观测性
- 账单、用量、订阅管理
- 项目设置、API 密钥、JWT、自定义域名、附加组件
- 集成市场、合规文档

## 特性

- **安全只读** — 仅替换页面上可见的英文文案，不读取、上传或修改你的 Supabase 数据
- **动态翻译** — 通过 MutationObserver 监听 DOM 变化，自动翻译弹窗、菜单、下拉框等动态内容
- **避开敏感区域** — 不会触碰 SQL 编辑器、代码块、密钥、连接字符串等敏感内容
- **智能匹配** — 支持固定词条精确匹配和正则表达式动态匹配

## 浏览器兼容

| 浏览器 | 支持 |
|--------|------|
| Chrome / Edge | 通过 Tampermonkey 或 Violentmonkey |
| Firefox | 通过 Tampermonkey 或 Violentmonkey |
| Safari | 通过 Tampermonkey |

## 许可

MIT
