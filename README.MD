##字符串分类提取器
###功能:
- 给出字符串的类型（getStringType()）
    1. 纯数字（num）
    2. 纯字母（char）
    3. 纯特殊字符（special）
    4. 数字+字母混合（num+char）
    5. 数字+特殊字符混合（num+spe）
    6. 字母+特殊字符混合（char+spe）
    7. 数字+字母+特殊字符混合（num+char+spe）


- 给出字符串相应类型的子串（getSubstringAllType()）
        eg. Input:123a@!bc
            Output:[('123', 'num'), ('a', 'char'), ('@!', 'spe'), ('bc', 'char')]
