# 钉钉 AI 精选项目

精选的钉钉 AI 应用实用工具列表，将 AI 能力快速应用到沟通、协同和业务中。

## 目录

- [AI Agent 框架](#ai-agent-框架)
- [MCP](#mcp)
- [机器人](#机器人)
- [实用 SDK](#实用-sdk)

## 项目列表


### AI Agent 框架

- [DingTalk Dify 连接器 - dingtalk-dify-connector](https://github.com/chzealot/dingtalk-dify-connector) - 把基于 Dify 构建的 Agent 接入到钉钉 AI 助理中。
- [DingTalk OpenWebUI 集成 - dingtalk-open-web-ui](https://github.com/xlb1130/dingtalk-open-web-ui) - 把OpenWebUI的能力接入到钉钉 AI 助理中。

### MCP

- [DingTalk Agent Client](https://github.com/darrenyao/dingtalk-agent-client) - 把钉钉客户端作为一个 MCP Host 使用

### 机器人

- [Dingtalk-OpenAI](https://github.com/ConnectAI-E/Dingtalk-OpenAI) - 基于 Go 语言实现的钉钉集成 ChatGPT 机器人
- [chatgpt-dingtalk-bot](https://github.com/anyidea/chatgpt-dingtalk-bot) - 官方浏览器版 ChatGPT 集成到钉钉机器人, 支持单聊和群聊
- [chatgpt-springboot-service](https://github.com/zccbbg/chatgpt-springboot-service) - 基于 Springboot 的一个后端服务，用于实时接收 ChatGPT 的消息，并通过 WebSocket 的方式实时反馈前端，基于Java开发
- [drone-dingtalk-messageDrone](https://github.com/lddsb/drone-dingtalk-messageDrone) -- Drone CI的钉钉群组机器人通知插件
- [bot-on-anything](https://github.com/zhayujie/bot-on-anything) -- 基于 Python 语言实现的将 ChatGPT、必应、文心一言、谷歌Bard 等对话模型连接各类应用，如微信、公众号、QQ、Telegram、Gmail、Slack、Web、企业微信、飞书、钉钉等

### <span id="sdk">实用 SDK</span>

【Open API SDK】

- [hugozhu/godingtalk](https://github.com/hugozhu/godingtalk) - DingTalk Open API golang SDK
- [CatchZeng/dingtalk](https://github.com/CatchZeng/dingtalk) - DingTalk(dingding) 是钉钉机器人的 go 实现
- [blinkbean/dingtalk](https://github.com/blinkbean/dingtalk) - Golang钉钉机器人客户端。支持文本、链接、Markdown、ActionCard、FeedCard类型消息的发送，Outgoing机器人消息的接收。
- [zhaoyunxing92/dingtalk](https://github.com/zhaoyunxing92/dingtalk) - Go版本的钉钉开发API
- [fastwego/dingding](https://github.com/fastwego/dingding) - 钉钉 A fast dingding development sdk written in Golang
- [prometheus-webhook-dingtalk](https://github.com/timonwong/prometheus-webhook-dingtalk) - DingTalk integration for Prometheus Alertmanager
- [DingtalkChatbot](https://github.com/zhuifengshen/DingtalkChatbot) - 钉钉群自定义机器人消息Python封装
- [dingtalk-sdk](https://github.com/007gzs/dingtalk-sdk) - 钉钉 dingding Python SDK。 DingTalk SDK for Python
- [dingtalk-python](https://github.com/blackmatrix7/dingtalk-python) - 钉钉第三方SDK，Python版本
- [ding-notice](https://github.com/wowiwj/ding-notice) - 钉钉推送机器人消息发送laravel扩展包


【Stream SDK】钉钉支持 Stream 模式接入 AI 助理、事件推送、机器人收消息以及卡片回调。相比 Webhook 模式，Stream 模式可以更简单的接入各类事件和回调，以下是各语言的 Stream SDK。

- [open-dingtalk/dingtalk-stream-sdk-python](https://github.com/open-dingtalk/dingtalk-stream-sdk-python) - Python
- [open-dingtalk/dingtalk-stream-sdk-go](https://github.com/open-dingtalk/dingtalk-stream-sdk-go) - Go
- [open-dingtalk/dingtalk-stream-sdk-nodejs](https://github.com/open-dingtalk/dingtalk-stream-sdk-nodejs) - Node.js
- [open-dingtalk/dingtalk-stream-sdk-java](https://github.com/open-dingtalk/dingtalk-stream-sdk-java) - Java
- [DingtalkChatbotSdk](https://github.com/yuzd/DingtalkChatbotSdk) - C#