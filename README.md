# @taktikangea/expedita-est(函数库)

## 概述

在开发中，我们经常会将一些常用的代码块、功能块进行封装，为的是更好的复用。那么，被抽离出来独立完成功能，通过 API 或配置项和其他部分交互，便形成了插件(工具函数)。
下面这些是我在工作中积累的一些常用的前端开源工具函数，需要读者根据自己的实际业务需求进行 install 安装,根据业务需求选用，涵盖率 80%以上，欢迎留言交流和补充。^\_^

另外，不要重复造轮子，把精力放在业务逻辑上！

## Install(安装)

npm install @taktikangea/expedita-est --save

## Usage(使用)

    1、防抖节流

    2、深拷贝

    3、浅拷贝

    4、call,apply,bind

    6、转义字符转换

    7、匹配字符串中所有图片src

    8、复制文本到粘贴板

    9、判断是浏览器内核

    10、获取HTML中的纯文本信息

    11、去除空格

    12、数字千分位分割(10,000,000)

    13、将阿拉伯数字翻译成中文的大写数字(五仟二百二十二)

    14、数字转为大写金额 （壹仟零伍拾贰万玖仟伍佰贰拾元整）

    15、文件大小格式化 (B,KB,MB,GB)

    16、动态加载外部样式文件

    17、异步加载外部多个js(动态插入)

    18、获取地址栏url参数

    19、手机号中间四位变成* (177****698)

    20、字符串首字母大写  （Hello）

    21、number边界处理

        1.大数相加

        2.大数相乘

    22、滚动条滚动

        1.动画缓冲(scrollAnimation)

        2.滚动页面到顶部(scrollToTop)

        3.滚动页面到底部（scrollToBottom)

    23、时间戳转格式

        1:YYYY-MM-DD HH:MM:SS

        2:刚刚、几天前、几个月前、几年前

        3:星期几

    24、随机数

        1:指定长度随机字符串

        2:范围内随机数

        3:数组取随机数

    25、6种排序方式

        1：冒泡排序

        2：计数排序

        3：插入排序

        4：归并排序

        5：快速排序

        6：选择排序

    26、数组

        1.扁平数据结构转Tree

        2.去重

        3.扁平化（降维）

    27、Base64

        1.加密

        2.解密

    28、UTF-8

        1.加密

        2.解密

    29、cookie

        1.设置

        2.获取

        3.移除

    30、常用校验

        1.邮箱校验

        2.手机号校验

        3.微信号校验

        4.QQ号校验

        5.车牌号校验

        6.密码强度校验

        7.是否包含中文校验

        8.邮编号校验

        9.16进制颜色校验

        10.身份证号校验

        11.Ipv4校验

        12.手机是Andoird还是IOS

        13.是否数字

        14.是否对象

        15.是否空对象

        16.是否数组

        17.数据类型判断

        18、银行卡号码校验（luhn算法）

        19.验证版本号格式必须为X.Y.Z

        20.验证护照（包含香港、澳门）
## 如何使用
``` language
import { deepCopy } from '@taktikangea/expedita-est';
```
``` language
const obj = {
  aa: 1,
  b: '52'
};
const text = deepCopy(obj);
```
## 欢迎大家提 PR 扩充函数库，为开源社区贡献自己一份力
git仓库连接：https://github.com/taktikangea/expedita-est

提 Pr 步骤  
1、src 底下创建自己模块函数的文件夹  
2、函数模块包含 markdow 说明，有自己测试用例（必须）  
3、根部 index.js 导出函数  
4、packjson keywords 里写自己函数关键字  
5、npm test 跑测试用例  
6、不要修改 packjson 版本号，版本号为线上最新用户使用版本  
7、Pull requests 测试用例过后，静等作者合代码  
8、代码合并后，作者会及时发布在 npm 上，更新修复版本

## Contact me(联系我)

![image](https://user-images.githubusercontent.com/25168173/154791040-09b5e289-5533-4aa2-9e6d-cb11eabfddf3.png)

## 我的博客

https://code-nav.top/blog

![image](https://user-images.githubusercontent.com/25168173/154791015-750d04e4-02d4-4ebb-a559-5e3331003309.png)

## License
