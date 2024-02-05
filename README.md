## 宝可梦 Rime 词库

目前更新到第九世代。  

各个文件对应：
- 宝可梦特性 luna_pinyin.pokemon_abilities.dict.yaml
- 宝可梦地区 luna_pinyin.pokemon_locations.dict.yaml
- 宝可梦技能 luna_pinyin.pokemon_moves.dict.yaml
- 宝可梦名称 luna_pinyin.pokemon_names.dict.yaml

一些提取规则：  
- 带有英文和数字的，删除
- 带有括号的，删除掉括号和括号中的内容。如果和已有的重叠，就忽略
- 对于这种带“・”的，比如“秘剑・千重涛”，则通过将“・”分割，得到两个新的词语

关于数据来源：  
来自 [神奇宝贝百科](https://wiki.52poke.com/wiki/%E4%B8%BB%E9%A1%B5)  
玩游戏时经常使用到该网站查询宝可梦数据，在此表示感谢。
