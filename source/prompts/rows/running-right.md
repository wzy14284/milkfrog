Create one horizontal animation strip for Codex pet `naiwa`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure magenta #FF00FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: 原创黄色胖奶蛙：巨大扁圆头与圆滚滚梨形身体连成一体，短粗胳膊，短小蹼脚，淡奶油色椭圆肚皮，两只鼓起的浅绿色半眯眼皮配深色小瞳仁，小塌鼻，宽阔的憨笑嘴；像奶龙的粗糙丑萌远亲但明确是青蛙，没有角、尾巴、龙鳞或背刺。光滑软胶3D玩具质感，表情呆滞又喜感。. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `3d-toy`: Stylized 3D toy mascot with smooth rounded forms, simple materials, clear silhouette, and no photoreal complexity. User style notes: 软胶玩具渲染，亮黄色主体、奶油白肚皮、浅绿色眼皮与蹼端；边缘干净，紧凑全身比例；参考图只用于理解胖圆黄蛙的丑萌轮廓，不复制背景、旗帜、群众、文字或原角色的具体设计。.
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
