# GPIO测试



##    测试项

包括：单色LED灯、双色LED灯、数码管、点阵、LCD触摸屏、复位键、拨码开关、按钮开关、矩阵键盘。

##    测试结果

  a. 16个单色LED灯 与 4x4矩阵键盘上的16个按键  对应，按一个亮一个；

  b. 双色LED灯         与 两个按钮开关中的上方那个 对应，按一下变色；

  c. 8个数码管          与 8个拨码开关对应，拨上则亮，且每个数码管会从0扫描显示到9；

  d. 点阵                    不停地自己刷新每一列每一行；

  e. LCD触摸屏         与 按钮开关下方按钮 配合，显示单周期CPU的状态，按钮开关充当 时钟，主要触摸屏的功能也要测试；

  f. 复位键                 用于复位全局。

  

 


