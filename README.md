# sgs_demo

三国杀身份场教学

12人局
角色：主公1人，忠臣4人，反贼6人，内奸1人

获胜条件：
主公：杀死所有反贼和内奸，即获胜
忠臣：跟主公一样
反贼：杀死主公，即获胜
内奸：全场只剩下内奸和主公，并且将主公击杀，即获胜
（注：当玩家的血量为空且全场没有桃或者技能救他时，则该玩家死亡。）

奖励和惩罚：（注：场上任何人在活着时候都不能亮出自己的身份牌，死亡后则必须亮出）
1.任何人杀死反贼，即可从牌堆里获得3张手牌
2.主公杀死忠臣，则主公失去所有牌

回合计算：每个人的回合分五个阶段
1.回合开始
2.判定开始
3.摸牌开始
4.出牌开始
5.弃牌开始

牌的分类：
1.基本牌（杀，雷杀，火杀，闪，桃，酒）
2.装备牌（武器，防具，+1马，-1马。每个人只能个装备一件，重复装备相当于替换）
3.锦囊牌

牌的响应：
1.当玩家A声明对玩家B打出一张杀，则玩家B必须响应（1.玩家B选择打出闪；2.玩家B受到一点伤害，掉一滴血）
2.当玩家A对自己或玩家B声明打出一张锦囊牌，则全场玩家可以选择响应（玩家B打出锦囊牌无懈可击，让玩家A的锦囊牌失效）
3.无懈可击可以重复被任何人的无懈可击牌给响应。（A：无中生有，B：无懈可击，A：无懈可击。结果A的无中生有生效，A从牌堆里摸两张牌）
4.针对AOE的锦囊牌，如：万箭齐发，南蛮入侵，桃园结义，五谷丰登等。需要每个人依次结算。重复规则2

延迟判定锦囊牌：
1.乐不思蜀：如果玩家A的武将上方有乐不思蜀的牌，则在玩家A的回合判定开始阶段，需要玩家A从牌堆顶部摸一张牌并亮出来，如果这张牌是红桃，则玩家可以进入出牌开始阶段，否则直接进入弃牌开始阶段
2.兵粮寸断：如果玩家A的武将上方有兵粮寸断的牌，则在玩家A的回合判定开始阶段，需要玩家A从牌堆顶部摸一张牌并亮出来，如果这张牌是草花，则玩家可以进入摸牌开始阶段，否则直接进入出牌开始阶段
3.闪电：如果玩家A的武将上方有乐不思蜀的牌，则在玩家A的回合判定开始阶段，需要玩家A从牌堆顶部摸一张牌并亮出来，如果这张牌是黑桃2-9，则玩家受到3点雷电伤害，否则闪电进入下一位玩家武将上方。
4.在判断开始阶段，全场任何人可以打出无懈可击，阻止延迟判定牌的结算。闪电则自动进入下一位玩家
5.过河拆桥和顺手牵羊可以对延迟判定锦囊牌生效





