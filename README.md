# 青年大学习自动签到脚本

Auto clock script for Young Study 

> 本项目目前处于测试阶段，欢迎参与测试并反馈结果给我
> 
> The repo is testing now, welcome to have a try and send issue to me.

## 项目介绍

本项目依赖Github Action功能定时任务实现每天自动打卡最新一期课程学习

The repo will automatically clock the newest class in Young Study Web depending on Github Action Schedule.

## 使用方法

1. 手机抓包获取`token`
2. Fork本项目
3. 新建环境变量`TOKEN`填入`token`值

- 如果想改变Github Action执行相关设置，请修改 [clock.yml](.github/workflows/clock.yml)

1. Get `token` by Capture
2. Fork the repo
3. New repositoty secret `TOKEN` and fill in `token`

- If you want to change Github Action, please edit[clock.yml](.github/workflows/clock.yml)

## License

本项目遵守`GPT3.0`开源协议

The repo is under `GPT3.0` License