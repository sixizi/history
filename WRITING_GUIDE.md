# 世界历史夜谈：第2—20篇写作与页面规范

每篇都是可独立阅读的中文 HTML 历史长文，面向初一学生和家长共同阅读。

## 内容标准

- 正文目标为8000—12000个中文字符，不能写成提纲、知识卡片或扩写后的目录。
- 从一个具体人物、家庭、城市或关键日子的场景进入，再逐层解释历史机制。
- 至少8个有连续逻辑的章节，覆盖来路、关键转折、普通人经验、不同立场、当代影响与结论。
- 明确区分可核实事实、历史记忆、政治立场和仍有争议的解释。
- 至少10条右侧边注，解释术语、数字口径、文件效力或史学争议。
- 至少2个“父子暂停一下”讨论框，结尾提供6个没有标准答案的问题。
- 至少8条可点击的可靠来源，优先原始文件、国际组织、政府档案、博物馆、大学与权威研究机构。
- 对仍在变化的战争、政策和人物状态注明“截至2026年8月”，不写未经核实的即时伤亡数字。
- 不把任何民族、国家或宗教画成天生的好人或坏人；解释不等于辩护。

## HTML结构

- 引用 article.css，不复制整套样式。
- body 添加 data-day，例如 data-day="02"。
- 顶部使用 hero，正文使用 layout > main.article + aside.toc。
- 每章使用 section.chapter 和唯一 id。
- 右侧注释使用 aside.sidenote。
- 史料说明使用 archive-note，讨论框使用 pause，不同叙事并列使用 perspective。
- 封面图固定为 images/dayNN-cover.png；图片是情境插画，图注必须声明“GPT Image 2生成，不是档案照片”。
- 顶部和底部提供“返回目录”“上一篇”“下一篇”链接。

## 文件与题目

- 02 day02-korea-division.html：朝鲜与韩国，一条纬线如何切开同一个民族
- 03 day03-north-korea-development.html：朝鲜的发展道路，安全国家与普通人的生活
- 04 day04-russia-ukraine-war.html：俄乌战争，从帝国边疆到全球震荡
- 05 day05-singapore-strategy.html：新加坡，小国如何在大国之间站稳
- 06 day06-berlin-wall.html：柏林墙，墙倒下以后统一才真正开始
- 07 day07-european-union.html：欧盟，把一部分主权交给共同规则
- 08 day08-cuban-missile-crisis.html：古巴导弹危机，世界最危险的十三天
- 09 day09-india-pakistan-kashmir.html：印巴与克什米尔，一次分家留下的伤口
- 10 day10-brexit.html：英国脱欧，拿回主权之后
- 11 day11-suez-panama-canals.html：苏伊士与巴拿马，谁控制世界的水门
- 12 day12-south-china-sea.html：南海，看不见的线与真实航道
- 13 day13-middle-east-oil.html：中东石油，黑色财富怎样改变国家命运
- 14 day14-hong-kong-singapore.html：香港与新加坡，两座港城的不同选择
- 15 day15-chips-digital-sovereignty.html：芯片战争，一粒沙子里的世界权力
- 16 day16-cyber-information-war.html：网络与认知战，看不见的战场
- 17 day17-climate-diplomacy.html：气候外交，谁发展、谁减排、谁付钱
- 18 day18-indian-ocean-red-sea.html：印度洋与红海，一条航线如何抵达餐桌
- 19 day19-nuclear-deterrence.html：核威慑，靠最可怕的武器阻止战争
- 20 day20-world-observation-system.html：台湾问题，海峡两岸为什么走到今天（末章保留六镜观察法）
