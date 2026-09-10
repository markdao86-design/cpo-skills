# 开源skill改造法
什么时候读我：手里有开源skill想改成自己的，或者要合并多个来源。

## 一、先跑不改(半小时)
1. 三个种子问题(用户原话)。
2. 原版skill跑一遍，无skill跑一遍。
3. 比：输出结构差多少、判断差多少、错误差多少。
4. 差不多的不改，选题本身可能就是"模型已经会了"。差很多的值得改。

## 二、拆骨架留肉
留下：框架名、步骤顺序、判据、评分表结构、反例。
换掉：它假想的行业、客户、公司名、例子、语言、输出格式。
删掉：与你选题无关的分支、营销话术、作者自我介绍。

## 三、许可证
| 许可证 | 能做什么 |
|---|---|
| MIT / Apache 2.0 | 随便改随便用，保留版权声明即可 |
| CC BY-SA | 可商用，改后要同许可证开源 |
| CC BY-NC / NC-SA | 只能借思路重写，不能搬段落进商用产品 |
| 无许可证 | 视为保留所有权利，只借思路 |

## 四、补三样它一定缺的
1. **硬门槛**：什么情况下这个skill不适用(如跨越鸿沟只对非连续创新有效)。
2. **反例**：用户和模型最常犯的错。
3. **业务锚**：你的公司、立场、口径、输出格式。

## 五、合并去重
多个来源同一框架(如三个仓库都有JTBD)：
1. 选最厚的那个当底。
2. 别的来源只补它没有的判据和反例。
3. 一个框架只出现一次，出现在最相关的那个skill里，别的skill用一句话指过去。

## 六、值得进料的开源仓库(2026-09)
PM侧：phuryn/pm-skills(MIT, 68技能, 骨架首选) / deanpeters/Product-Manager-Skills(NC, 借思路) /
product-on-purpose/pm-skills(Apache, 200样例+critic子agent) / Digidai/product-manager-skills(NC, PRD批判) /
huntsyea/product-skills(MIT, Torres/JTBD/ShapeUp/StoryMap)
UX侧：tommyjepsen/awesome-ux-skills(AI产品设计六模式) / szilu/ux-designer-skill(MIT, 万行参考) /
cuellarfr/design-skills(MIT, 交互设计与设计批判)
