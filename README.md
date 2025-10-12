<div align="center">

![new-api-horizon](https://github.com/Calcium-Ion/new-api/blob/main/web/public/logo.png)

# New API Horizon

特性版 - 基于New API开发的增强版本

<p align="center">
  <a href="https://github.com/Calcium-Ion/new-api/releases/latest">
    <img src="https://img.shields.io/github/v/release/Calcium-Ion/new-api-horizon?color=brightgreen&include_prereleases" alt="release">
  </a>
  <a href="https://hub.docker.com/r/CalciumIon/new-api-horizon/tags">
    <img src="https://img.shields.io/badge/docker-dockerHub-blue" alt="docker">
  </a>
</p>
</div>

</div>

## 关于New API Horizon

New API Horizon是基于开源项目[New API](https://github.com/Calcium-Ion/new-api)开发的特性版本。它保留了原版的核心功能,同时增加了一些新的特性和改进。这个版本不开源,但免费提供给用户使用。

## 获取方式

Docker镜像：calciumion/new-api-horizon:latest

## 新增特性

除了原版New API的所有功能外,New API Horizon新增以下特性

1. 优化部分场景导致CPU 100%占用的问题（注意，此功能并非修复了newapi的bug，而是通过技术手段提升性能，没有在开源版本的代码里故意留bug留到horizon修复，请勿造谣）
2. 新增系统设置-性能设置，Docker部署下启用流模式性能优化可减少约5%的CPU占用

