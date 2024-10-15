<div align="center">

![new-api-horizon](https://github.com/Calcium-Ion/new-api/blob/main/web/public/logo.png)

# New API Horizon

特性版 - 基于New API开发的增强版本

</div>

## 关于New API Horizon

New API Horizon是基于开源项目[New API](https://github.com/Calcium-Ion/new-api)开发的特性版本。它保留了原版的核心功能,同时增加了一些新的特性和改进。这个版本不开源,但免费提供给用户使用。

## 获取方式

Docker镜像：calciumion/new-api-horizon:latest

## 新增特性

除了原版New API的所有功能外,New API Horizon新增以下特性

1. **[OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime/integration)** - 支持OpenAI的Realtime API，支持Azure渠道。
2. 支持`/v1/messages`接口（兼容OpenAI渠道转换为Claude格式）

## WIP

1. [ ] 针对渠道的RPM限制
2. [x] 支持自定义令牌聊天选项
3. [x] 支持自定义充值选项
4. [x] 支持/v1/messages接口（兼容OpenAI渠道转换）