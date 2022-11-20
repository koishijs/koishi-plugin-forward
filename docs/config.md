# 配置项

## 基础设置

### storage

- 类型：`'database' | 'config'`
- 默认值：`'config'`

转发规则的存储方式。

### rules

- 类型：`Rule[]`

转发规则列表。详见 [转发规则](#转发规则)。

### replyTimeout

- 类型：`number`
- 默认值：`3600000`

转发消息不再响应回复的时间 (毫秒)。

## 转发规则

### rule.source

- 类型：`string`
- 必须参数

来源频道。

### rule.target

- 类型：`string`
- 必须参数

目标频道。

### rule.selfId

- 类型：`string`
- 必须参数

负责推送的机器人账号。

### rule.guildId

- 类型：`string`
- 必须参数

目标频道的群组编号。
