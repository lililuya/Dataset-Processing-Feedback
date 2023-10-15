# 9月2日427人数据整理

## 1.数据整体统计

**原拍摄图片**

+ 共**427**人，**2732**张
+ 图片分辨率：**7008*****4672**

**参数设置**

+ **FFHQ **裁剪方式
+ **png **图片保存
+ **min size** 选择**0.7**

**处理后的图片**

+ 采集得到2712张高清人脸图（部分图片有多张清晰人脸）

+ 得到人脸图分辨率：**1024*****1024**

## 2.主要几类问题的汇总

+ 颜色过暗：几乎无法辨认五官
+ 遮挡面积过大：几乎遮挡了60%的五官
+ 侧脸角度过大：侧脸超过90度
+ 运动模糊：脸部不清晰，发丝部分出现重影
+ 单ID数据过少：同一个人的脸部数据小于等于2

## 3.数据集的主要问题

### （1）颜色过暗

#### **例1：DSC01685.jpg** 

> ![image-20231014172410775](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014172410775.png)

---



**例2：DSC03228.jpg**

> ![image-20231014173438437](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014173438437.png)

---



**例3：DSC03293.jpg**

> ![image-20231014173526451](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014173526451.png)

---



### **（2）严重失焦**

**例1：DSC02748.jpg**

> ![image-20231014173710921](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014173710921.png)
>
> ![image-20231014173722721](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014173722721.png)

----



### **（3）遮挡面积过大**   

  **例1：DSC02204.jpg**

> ![image-20231014174017906](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174017906.png)

---



**例2：DSC02956.jpg**

> ![image-20231014174032229](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174032229.png)

---



**例3：DSC03079.jpg**

> ![image-20231014174041427](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174041427.png)

---



**例4：DSC02530.jpg**

> ![image-20231014174050160](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174050160.png)

---



**例5：DSC04305.jpg**

> ![image-20231014174058433](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174058433.png)

---



**例6：DSC04304.jpg**

> ![image-20231014174115117](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174115117.png)

----



**例7：DSC03152.jpg**

> ![image-20231014174127346](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014174127346.png)

---



### **（4）侧脸角度过大**

**例1：DSC03136.jpg**

> ![image-20231014180745947](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014180745947.png)

---



### **（5）运动模糊**

**例1：DSC01974.jpg**

> ![image-20231014181148594](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181148594.png)
>
> <img src="C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181154952.png" alt="image-20231014181154952" style="zoom: 80%;" />

---



 **例2：DSC01970.jpg**

> ![image-20231014181209619](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181209619.png)
>
> ![image-20231014181213498](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181213498.png)

---



  **例3：DSC02021.jpg**

> ![image-20231014181223340](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181223340.png)
>
> ![image-20231014181227753](C:\Users\liwen\Desktop\数据集的整理\images\image-20231014181227753.png)

---



**例4：DSC01666.jpg**

> ![image-20231014181541051](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014181541051.png)
>
> ![image-20231014182016425](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182016425.png)

---



**例5：DSC01698.jpg**

> ![image-20231014182028138](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182028138.png)
>
> ![image-20231014182032690](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182032690.png)

---



**例6：DSC01879.jpg**

> ![image-20231014182049075](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182049075.png)
>
> ![image-20231014182053824](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182053824.png)

---



**例7：DSC01885.jpg**

> ![image-20231014182106059](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182106059.png)
>
> ![image-20231014182111422](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182111422.png)

---



**例8：DSC01892.jpg**

> ![image-20231014182121307](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182121307.png)

---



**例9：DSC02748**\

> ![image-20231014182130118](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182130118.png)
>
> ![image-20231014182136517](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182136517.png)

---



**例10：DSC02911.jpg**

> ![image-20231014182146274](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182146274.png)
>
> ![image-20231014182152602](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182152602.png)

---



**例11：DSC03174.jpg**

> ![image-20231014182243581](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182243581.png)
>
> ![image-20231014182248412](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182248412.png)

---



**例12：DSC03286.jpg**

> ![image-20231014182301366](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182301366.png)
>
> ![image-20231014182305062](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182305062.png)

### **（6）单个ID数据过少**

**例1：DSC03798.jpg（2张）**

> ![image-20231014182328479](C:\Users\liwen\Desktop\数据集的整理\Dataset-Processing-Feedback\images\image-20231014182328479.png)

---

