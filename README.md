






**好好学习 天天向上**

修改来源于：[LazyStudy](https://github.com/lolisaikou/LazyStudy)


[Hamibot_Study](https://hamibot.com/marketplace/1Kw2X?invite=ONTRWIBaZqdBWuDk6DNzT7rt)
---
## 免责声明

**本脚本为免费使用，本脚本只供个人学习使用，不得盈利传播，不得用于违法用途，否则造成的一切后果自负！**

**对本仓库代码进行修改再创作必须声明出处**

---
- 功能：文章学习、订阅、评论分享、视频学习、每日答题、挑战答题、每周答题，专项答题、四人赛、双人对战。
 - 四人/双人赛：hamibot内置文字识别(OCR)、百度文字识别(OCR)、第三方本地文字识别(OCR)
 - **hamibot内置文字识别(OCR)与第三方本地文字识别(OCR)识别速度与设备硬件有关。一般速度快于百度/华为文字识别(OCR)**
 - hamibot内置文字识别(OCR)：需要hamibot 1.3 以上，**部分机型识别较慢,则换其他OCR使用。**
 - 百度文字识别(OCR)需要配置 API Key 和 Secret Key：[教程](https://cloud.baidu.com/doc/OCR/s/dk3iqnq51)
 - 第三方本地文字识别(OCR)插件 [点击这里下载](https://twelve123.lanzouq.com/b017az0kj)[密码:7faj]
 - 32位适合hamibot 1.1版本
 - 旧手机和模拟器使用32位第三方OCR插件

- 全功能支持ys模拟器 **安卓9**
 
		1. 模拟器配置(安卓 9）
 		2. hamibot v1.1.0版本
 		3. qg 2.33.0版本及以下
 		4. Study视频学习选择新百灵视频  四人模式选择百度/华为OCR或第三方OCR插件
 - [电报交流群](https://t.me/+A4KV10N9_gJmZTE1)
 - **一张图片、一句话，并不能解决问题。**
 - **完整日志内容才能解决问题**

---

## 2022.03.23.731
- 优化乱序模式的选项搜索
---

## 2022.03.22.728
- 优化乱序模式
- 增加四人/双人单选开关

---

## 2022.03.20.711
- 增加答题类型，自选按键

---

## 2022.03.19
- 因qg更改题目选项顺序，使得顺序为随机出现，需要等待选项出现再进行答题

---
##  2022.03.16.670
- 修复因2022.03.08.633版本的改进,导致挑战答题错误率高的BUG

---
##  2022.03.15.669
- 增加：看门狗-----设置最长脚本运行时间，超时或报错则自动重新运行。

---
## 2022.03.13.648
- 累计报错优化
- 增加 **遇到错误则自动重启脚本** 选项开关

---
## 2022.03.08.633
- 优化部分类型题的搜索
---
## 2022.03.06.623
- 增加使用须知
---
## 2022.03.04.617
- 加个进度条
- 设置在hamibot界面预加载题库
---
## 2022.03.02.602
- 去除一行可能造成搜错题的代码
- 一些其他地方的改进
---
## 2022.03.01.599
- 修复因识别错误导致未搜到题而造成报错
- 优化点点通

---
## 2022.02.27.595
- 去除随机模式选项--默认随机模式
- 完善四人/双人搜题逻辑
- 去除本地题库，修改为实时加载（避免部分手机存储异常）
- 增加刷满点点通（测试）

---
## 2022.02.25.570
- 根据近一个月大家反馈的错题错字，重写了部分四人/双人搜题逻辑

---

## 2022.02.14.539
- 增加每日、每周、专项答题增强模式 - 使用云端OCR进行文字识别(本地ocr识别准确度较低，故不采用) 
---

## 2022.02.11.529

 1. 解决部分人挑战答题异常；
 2. 优化每日答题、每周答题、专项答题的填空类型题目，将在此时调用百度OCR或华为OCR进行文字识别正确的填空答案（如果填入了百度OCR或华为OCR的配置的话）
 - **注意：想要提高填空题正确率--只需填百度或华为配置即可，与四人/双人的OCR选择不冲突**

---

## 2022.02.09.523

 1. 四种OCR选择；
 2. 增加四人/双人额外一轮乱答模式；
 3. 挑战答题题库修改；
 4. 四人/双人答题优化：从400ms以下依次测试---400->300->250->200->150->100->0,找到适合自己手机的延迟(既不卡住也不输)；
 5. 增加读音字形题错字的替换；
 6. **四人/双人暂时存在的问题**：读音字形题需要等待选项出现才进行文字识别，所以该类型题答题较慢 且 一旦文字识别出现错字则难以搜题。
   -  [电报交流群](https://t.me/+A4KV10N9_gJmZTE1)
----

## 2022.02.03.510

 1. 由于配置内容过多，将华为ocr替换为百度ocr：[教程](https://cloud.baidu.com/doc/OCR/s/dk3iqnq51)
 2. 订阅问题修改
 
----

## 2022.01.25.486

 1. 优化部分人的订阅
 2. 增加[push+(推送加)](https://pushplus.hxtrip.com/index) ：有需要则填写Token
 

---
## 2022.01.24.472更新

 - 增加答题之前的检测

---
## 2022.01.22.467更新
1. 一个大胆的尝试：重写搜题算法，可能答题不再受文字识别的错字影响；
2. 测试阶段所有ocr均可不受积分限制答题；
3. 如果四人/双人赛答错，请截图日志；
4. 仔细查看Study配置内容。

---

## 2022.01.09.358更新

 1. 优化代码
 2. 增加熄屏点亮

---

## 2022.01.08.351更新

 1. 重构四人赛双人赛答题逻辑（大概率获胜）
 2. 增加 hamibot 内置 ocr (文字识别) ------需要 [hamibot 1.3.0-beta.1](https://hamibot.cn/download) 及以上的版本
 3. 优化一些小细节

---


 
![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/d14b5725b7463db01c17a677bdfc06d8.png#pic_center)
