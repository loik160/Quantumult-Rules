# Quantumult-Rules
夕立之音 - リバティRule for Quantumult,导入后只替换配置文件中的[TCP]规则,不会造成其他数据损失(当前文件的节点,DNS,POLICY等数据均会保留),本规则属于轻量级规则,8个月从4000条精简到700+条,其中主要去除了重复和一些无效网址,合并了冗余网址,另外要说明的是本规则没有对微博、网易进行相关去广告处理,如无大的bug,后续可能不会有大更新。

4000条模板为doubi极客，中间参考过lhie1和cloud gate dalao的一些东西，自己也做了一些修改。 感谢以上dalao
******************************************************************************************************************************************

                                                  使用方法：

******************************************************************************************************************************************

订阅RULE规则：打开Quantumult,点击Settings-Favorites-"右上角加号"-FILTER

Name随意,URL地址填写为：https://raw.githubusercontent.com/unknowntokyo/Quantumult-Rules/master/Quantumult.conf  （后续不会做太大更新）

或者URL地址填写为：https://raw.githubusercontent.com/lhie1/Surge/master/Quantumult.conf  (2017.7.24添加到@lhie1官方支持，同步更新)

订阅URL-REJECTION规则：打开Quantumult,点击Settings-Favorites-"右上角加号"-URL-REJECTION

添加URL地址为：https://raw.githubusercontent.com/unknowntokyo/Quantumult-Rules/master/URL-REJECTION.conf

点击save之后,左划刚刚添加的Filter,点击Append即可添加规则到本地

区别：

Quantumult.conf为轻量，我自己修改的

2017.8.4 添加：

[MITM]-hostname 来自@lhie1的规则，引用源地址为：https://github.com/lhie1/Surge/blob/master/Hostname.conf

URL-REJECTION.conf 来自@lhie1的规则，引用源地址为：https://github.com/lhie1/Surge/blob/master/URL_REJECT.conf
