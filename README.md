# xnhewubi_feijian

*rime-feijian

*本地词库，无安全隐患。

*高度客制化，自定映射。

*搭载明月词库为基础的小鹤双拼副翻译器。

## 小鹤五笔音形输入法-对侧飞键版

### 简单介绍（introduce）：

  小鹤音码配合五笔形码辅助码、小鹤五笔zh/ch/sh对侧击键飞键版，击键当量等同五笔，键长优于小鹤音形。
  
  对侧击键率51%、码长2.20。

  需要特殊记忆的编码如下：

  现：xg 实：up 仅：jw 字：zp 及：je 种：ot 任：rw 妹：mv 为：wy 和：ht 网：wm 子：zb 阿：ab 时：uj 物：wt

### 飞键映射（map）：

  /shi-us/feng-fs/  (增加s按键频率)
  
  /ang-am/ao-ac/

  /eng-am/ei-ew/

  /右韵母zh-v/左韵母sh-u/左韵母ch-i/  (同原版小鹤一致)
  
   /左韵母zh-o/右韵母sh-a/右韵母ch-e/  (对侧映射)
  
### 特点:

  优点：不需要特殊学习，会五笔和小鹤即可使用，难度不算高。
  
  兼容整句及打单，使用范围广。
  
  拆分了zh/ch/sh等易导致双拼ui高频率的声母，使得按键热力图比一般双拼更合理。
  
  # 击键当量(value):
  
![image](https://user-images.githubusercontent.com/49089769/231258004-437d7475-aa7b-41fa-9b18-55ed12058848.png)

![image](https://user-images.githubusercontent.com/49089769/231267199-d955b5b9-0b21-4b30-9a21-3d6d6d464b49.png)

![image](https://user-images.githubusercontent.com/49089769/231257600-4157aaef-848b-4b0a-bcae-f32233811024.png)

### 关于热力图(hot-map):

*赛码器的一个算法会导致逗号不被按下，而被算入按键编码，因此这是去除了简码表内的逗号编码后的结果。

*显示缺少汉字是因为只包含了txt内的汉字码表，全码表在dict.yaml文件内，由于dict.ymal使用的是正则规则，容易导致显显示码长高于正常情况，没有放入赛码器内。

*部分一简码（如花，编码为h;）使用分号选重，会导致重码率偏高，而分号按键当量偏低。

*音码码表和形码码表不同，赛码器内各项显示数值会偏高。

*测试优化仅仅是同时添加了对应的简体并去除了多余的标点，没有做额外的改动。

### 如何使用该输入法(install):

  *下载[Rime-小狼毫](https://github.com/rime/squirrel/releases)，安装后右键点击【ㄓ】进入用户文件夹，将该方案置入小狼豪用户文件夹内。
  
  ![image](https://user-images.githubusercontent.com/49089769/231263797-801e79b0-7b3c-45e2-91eb-1d2d60a750c7.png)

  右击【ㄓ】选择输入法设定，勾选该方案，即可使用。

  默认为简体，通过快捷键 Control+ J 切换繁简。

  输入 ob 呼出五笔及拆字模式（例：oblslsls = 龘），obhelp 呼出飞键提示，obinfo呼出更多信息。
    
*五笔：
  
  ![image](https://user-images.githubusercontent.com/49089769/231264279-6783625f-6f1c-4cdd-9ddc-a4b6560d5875.png)


*拆字：
  
  ![image](https://user-images.githubusercontent.com/49089769/231264140-bb00a0f3-6c96-4b9c-8294-ac5850fce443.png)
  
  ![image](https://user-images.githubusercontent.com/49089769/231264822-8e3b34b9-d0cc-4f22-acad-4e1b29d6801a.png)

  


