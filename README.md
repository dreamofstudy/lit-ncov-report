# lit-ncov-report
洛阳理工学院 “健康状况管控平台” 每日自动上报

![test](https://raw.githubusercontent.com/icepie/lit-ncov-report/master/docs/run.png) 
## how to use
1. 准备好`python3`环境
2. 安装所需依赖：`pip3 install -r requirements.txt` 或者 `make init`
3. 运行程序:`python3 main.py` 或者 `make run`
4. 使用参数: `-u <username> -p <password> [m]`
## todo
- [x] 登录
- [x] 报告
- [ ] 定时报告
- [x] 批量报告
- [ ] tgbot提醒