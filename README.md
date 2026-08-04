# education

三年级（约 9 岁）科学课程内容仓库。全中文。

当前重心：**深化课案 + 每课约 90 秒脚本**。

## 快速开始

1. 大纲地图：[`curriculum/L1/总览.md`](curriculum/L1/总览.md)
2. 怎么上课：[`curriculum/课案/总览.md`](curriculum/课案/总览.md)
3. 90 秒脚本：[`curriculum/L3/视频/总览.md`](curriculum/L3/视频/总览.md)

| 层级 | 内容 | 状态 |
|------|------|------|
| L1 | 24 单元通俗大纲 | 完成 |
| 课案 | 每课开场/演示/主任务/金句 | 24 课完成 |
| L2 | 难度细化 | 初版在 |
| L3 视频 | 约 90 秒脚本 | 24 课完成 |
| L3 互动 | 互动 JSON | 3 示范 |

## 生成脚本

```bash
python3 scripts/generate_l1_outlines.py      # L1 通俗大纲
python3 scripts/generate_lessons_and_90s.py  # 课案 + 90 秒脚本
python3 scripts/generate_curriculum.py      # L2 等（旧批量）
```
