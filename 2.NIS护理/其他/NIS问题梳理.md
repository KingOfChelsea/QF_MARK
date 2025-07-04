# NIS问题梳理

## 1.血压待测单

1. 根据下面这张图是有9个时间点，满不满足现在医院的需求？有没有一小时测一次
   ==24小时，心电监护==

   ![img_v3_02nj_900995f0-130b-441b-8d87-44dbd7e7b6eg](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/img_v3_02nj_900995f0-130b-441b-8d87-44dbd7e7b6eg.jpg)

2. 创建完血压单：

   1. 有创建护理记录的患者能够会显示到血压待测中 
   2. 所有点都能录入，但是有对应医嘱的会在对应的点有阴影背景提示 

3. 全院的科室是否有一份通用的护记表单能够录入血压 

   ==儿科、新生儿科、妇产科、产科、产科新生儿科、临终患者==

4. 护理记录显示的血压时间是整点的记录不会精确到实际的时间

   ==接受==

## 2.患者早期预警值

- [x] 这张表就是个规则，在录入这些数值的时候，校验规则，触发弹窗提醒

   ![image-20250626120204012](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250626120204012.png)

## 3.面部表情法和数字评分表需要结合

- [x] 功能上数字评分法满足祈福医院的需求，希望在对应的坐标上加上彩色表情图片以及对应的节点说明，这些作用只为了展示提醒作用！（这边护士长，主任要求这么做的）

![image-20250626120753172](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250626120753172.png)

## 4.核对医嘱界面过于复杂

---

## 5.护理计划

1. 护士接受新开立特殊医嘱时，自动进入护理计划待诊断列表
2. 护理记录自定义列，描述特殊内容（咳嗽、管道等）时，自动进入护理计划待诊断列表
3. 不同科室针对患者病情的不同检查检验结果，自动进入护理计划待诊断列表（建议护理记录引用检验检查结果时自动带入护理计划）

---

## 6.转科记录 

- [ ] 体温单上显示不出来
- [ ] 护记上的内容最好都要显示

## 7.体温录入规则

- [ ] 可以随意录，自己操作

## 8.护理记录一项的内容过多希望可以自动换行（win限制）

- [x] ![image-20250701170600348](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250701170600348.png)

## 9.评估表需要显示儿童的天数，比如28天怎么填写

- [x] ![image-20250701150913775](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250701150913775.png)

## 10.住院流水号显示

- [ ] 现在是住院流水号，转为住院号

## 11.产程图肿中的数据需要从护记中带过来(血压、胎心、宫缩、先露高低)，数据抓取需要从产前待产记录+催产素使用记录表中抓取数据

<span style="background-color: yellow; font-size:28px; font-weight: bold;">优先沟通</span>

- [ ] 产前待产记录+催产素使用记录表（抓取血压、胎心、宫缩、先露高低），总结：产程图的数据需要从护记中同步过去
- [ ] ![1feeb3ff27d64017ce91c6a4d0e8665b](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/1feeb3ff27d64017ce91c6a4d0e8665b.png)

## 12. 移动护理能使用会诊功能吗？no

- [x] 有多学科护理会诊功能，可在**PDA或pad上进行**，并有会诊次数统计

## 13.曲线图不显示对应的评估

<span style="background-color: yellow; font-size:28px; font-weight: bold;">显示问题</span>

<video src="https://gitee.com/HavertzPlatform/worker-picgo/raw/master/2025-07-01 18-11-14.mp4"></video>

## 14.护士站对于级别护理颜色的区分

- [x] ==**我们三级护理是绿色的，改为不标记**==

![image-20250702084400240](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250702084400240.png)

## 15.元素组件翻页是否更新

---

## 16.体温问题



## 17.婴儿住院号问题

![image-20250702180849534](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250702180849534.png)

## 18 RRT规则是否匹配

- [ ] rrt规则

## 19 疼痛的图

- [ ] 目前使用操作，会打印出来，

![image-20250702181442331](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250702181442331.png)

## 20 审核人签名

- [ ] jira，

![image-20250702181751616](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250702181751616.png)

## 21.血糖

## 22.血压待测单

---

## 23.事件时间

---

## 24.打印√选择措施

之前那个dll文件那个不好使

![image-20250704151624812](https://gitee.com/HavertzPlatform/worker-picgo/raw/master/image-20250704151624812.png)

<video src="https://gitee.com/HavertzPlatform/worker-picgo/raw/master/2025-07-04 15-00-40.mp4"></video>

<video src="https://gitee.com/HavertzPlatform/worker-picgo/raw/master/2025-07-04 14-52-37.mp4"></video>

## 25.

