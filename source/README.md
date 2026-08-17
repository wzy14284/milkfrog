# Source notes

`strips/` 保存每个动画状态在确定性帧提取前的完整生成长条；`prompts/` 保存对应的生成规格。`spritesheet.png` 是完成透明背景处理后的无损 v2 图集，`atlas-layout.json` 描述 16 个环视方向的行列位置。

`running-left.png` 是从已批准的 `running-right.png` 逐帧水平镜像得到的确定性派生行，以保留原步态顺序。
