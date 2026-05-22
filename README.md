# 群报数签到自动化模板

这是一个用于探索“群报数签到自动化”的模板项目。

## 文件说明

- `students.example.txt`：匿名学生名单示例。
- `courses.example.csv`：匿名课程表示例。
- `config.example.json`：AutoX 配置示例。
- `ai_config.example.json`：AI API 配置示例。

## 项目结论

传统 AutoX 固定点击脚本在微信小程序、地图定位、QQ 发图这类流程里不够稳定。

更可行的方向是：

1. 先做课前提醒、课程标题、时间范围、名单复制等辅助功能。
2. 如果继续自动化，优先尝试 AI 视觉 Agent。
3. 发 QQ 群前建议保留人工确认，避免误发。
