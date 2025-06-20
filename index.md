---
layout: home
title: 天气查询系统设计完整博客
---

# 项目名称
天气查询系统

## 项目简介
天气查询系统是一款基于 Java Swing 的桌面应用程序，旨在为用户提供便捷的天气查询服务。用户可以通过登录系统查看当前城市的天气信息，并支持切换城市、修改背景图片等功能。系统采用模块化设计，易于扩展和维护。

## 项目采用技术

|技术|描述|
|-|-|
|Java Swing|用于实现桌面应用程序的图形用户界面 (GUI)。|
|MySQL|用于存储用户信息、城市编码和天气数据。|
|Maven|用于项目构建和依赖管理。|
|Jsoup|用于从天气网站抓取天气信息。|
|Git|用于版本控制和团队协作。|

## 功能需求分析
1. 用户管理
- 用户注册：支持用户注册，填写用户名、密码、密保问题和地区。
- 用户登录：验证用户名和密码，登录系统。
- 密码重置：通过密保问题验证后重置密码。
2. 天气查询
- 自动显示用户所在地区的天气信息。
- 支持切换城市，动态更新天气信息。
3. 界面设置
- 支持修改窗口大小（小、中、大）。
- 支持更改背景图片（春、夏、秋、冬）。
4. 数据管理
- 城市编码和天气信息存储在 MySQL 数据库中。
- 支持从数据库动态加载城市列表和天气信息。

## 项目亮点
1. 模块化设计：
- 用户管理、天气查询、界面设置等功能模块独立，便于维护和扩展。
2. 动态天气更新：
- 使用 Jsoup 从天气网站抓取实时天气信息，并存储到数据库中。
3. 个性化设置：
- 用户可以根据个人喜好调整窗口大小和背景图片。
4. 数据库集成：
- 使用 MySQL 存储用户信息和天气数据，确保数据持久化。
5. 团队协作：
- 使用 Git 进行版本控制，团队成员分工明确，协作高效。

## 主要功能截图

### 主要功能截图
1. 登录界面  
  <div align="center">
    <img src="images/login.png" alt="登录界面" width="400">
  </div>
2. 注册界面
  <div align="center">
    <img src="images/register.png" alt="注册界面" width="400">
  </div>
3. 修改密码界面
  <div align="center">
    <img src="images/changepassword.png" alt="修改密码界面" width="400">
  </div>
4. 主页面  
  <div align="center">
    <img src="images/app.png" alt="主页面" width="400">
  </div>
5. 其它功能  
  <div align="center">
    <img src="images/setting.png" alt="其它功能" width="400">
  </div>

## 团队成员负责模块

|姓名|GitHub用户名|负责模块|主要工作|
|-|-|-|-|
|刘乐飞|LiXinGDBW|数据库，工具类与天气查询模块|构建AppJFrame,DatabaseUtils,WeatherInfoManager和WeatherUtils，数据库更新与修改；使用 Jsoup 抓取天气数据并存储到数据库中；完成天气查询功能的实现。|
|魏祥涵|suisuiyuanpingan|用户管理模块|构建LoginJFrame,RegisterJFrame和UserUtils，实现用户注册和登录功能。|
|张博文|ZBW-king|界面设置与背景管理模块|构建App,BackgroundUtils和RechangePasswordJFrame，实现窗口大小调整和背景图片更改功能；实现用户更改密码功能。|

## 项目Git地址
[https://github.com/LiXinGDBW/WeatherApp](https://github.com/LiXinGDBW/WeatherApp)

## 成员github地址
- 刘乐飞：[https://github.com/LiXinGDBW](https://github.com/LiXinGDBW)
- 魏祥涵：[https://github.com/suisuiyuanpingan](https://github.com/suisuiyuanpingan)
- 张博文：[https://github.com/ZBW-king](https://github.com/ZBW-king)

---
