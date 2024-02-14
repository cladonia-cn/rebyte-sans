<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-light.png">
  <img src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-normal.png">
</picture>

![preview-01](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/preview-01.png)
![preview-02](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/preview-02.png)

---

> [!NOTE]
> Useful information that users should know, even when skimming content.

<details>

<summary>
新增的 OpenType 特性
</summary>

( 相较于原版 [Figtree](https://github.com/erikdkennedy/figtree) ) 

## Liga
##### 替换
<details>

<summary>
GSUB Features
</summary>


    /* 版权与许可符号
    sub parenleft C parenright by copyright;
    sub parenleft R parenright by registered;

    /* 箭头
    sub slash greater by northeastarrow;
    sub less slash by southwestarrow;
    sub less backslash by southwestarrow;
    sub less minus by leftwardsarrow;
    sub equal slash by notequalto;
    sub equal less by lessthanorequalto;
    sub greater equal by greaterthanorequalto;
    sub backslash equal by northeastarrow;
    sub minus greater by rightwardsarrow;
    
    /* yt 特殊样式连字
    sub y t by y_t.liga;

</details>

<details open>

<summary>
Preview
</summary>

![opentype-03](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-03.png)
![opentype-04](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-04.png)
![opentype-05](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-05.png)
![opentype-06](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-06.png)
![opentype-07](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-07.png)

</details>

---
## Kern
##### 间距
<details>

<summary>
GSUB Features
</summary>

    //时钟冒号居中
    pos colon zero <0 90 0 0>;
    pos colon one <0 90 -10 0>;
    pos colon two <0 90 -45 0>;
    pos colon three <0 90 -50 0>;
    pos colon four <0 90 -10 0>;
    pos colon five <0 90 -10 0>;
    pos colon six <0 90 -15 0>;
    pos colon seven <0 90 0 0>;
    pos colon eight <0 90 -15 0>;
    pos colon nine <0 90 0 0>;

    // 短划线居中
    /* 大写字符
    pos minus A <0 60 -60 0>;
    pos minus B <0 60 0 0>;
    pos minus C <0 60 0 0>;
    pos minus D <0 60 0 0>;
    pos minus E <0 60 0 0>;
    pos minus F <0 60 0 0>;
    pos minus G <0 60 0 0>;
    pos minus H <0 60 0 0>;
    pos minus I <0 60 0 0>;
    pos minus J <0 60 0 0>;
    pos minus K <0 60 0 0>;
    pos minus L <0 60 0 0>;
    pos minus M <0 60 0 0>;
    pos minus N <0 60 0 0>;
    pos minus O <0 60 0 0>;
    pos minus P <0 60 0 0>;
    pos minus Q <0 60 0 0>;
    pos minus R <0 60 0 0>;
    pos minus S <0 60 0 0>;
    pos minus T <0 60 0 0>;
    pos minus U <0 60 0 0>;
    pos minus V <0 60 0 0>;
    pos minus W <0 60 0 0>;
    pos minus X <0 60 0 0>;
    pos minus Y <0 60 0 0>;
    pos minus Z <0 60 0 0>;

    /* 小写字符
    pos minus a <0 -40 0 0>;
    pos minus b <0 -40 0 0>;
    pos minus c <0 -40 0 0>;
    pos minus d <0 -40 0 0>;
    pos minus e <0 -40 0 0>;
    pos minus f <0 -40 0 0>;
    pos minus g <0 -40 0 0>;
    pos minus h <0 -40 0 0>;
    pos minus i <0 -40 0 0>;
    pos minus j <0 -40 0 0>;
    pos minus k <0 -40 0 0>;
    pos minus l <0 -40 0 0>;
    pos minus m <0 -40 0 0>;
    pos minus n <0 -40 0 0>;
    pos minus o <0 -40 0 0>;
    pos minus p <0 -40 0 0>;
    pos minus q <0 -40 0 0>;
    pos minus r <0 -40 0 0>;
    pos minus s <0 -40 0 0>;
    pos minus t <0 -40 0 0>;
    pos minus u <0 -40 0 0>;
    pos minus v <0 -40 0 0>;
    pos minus w <0 -40 0 0>;
    pos minus x <0 -40 0 0>;
    pos minus y <0 -40 0 0>;
    pos minus z <0 -40 0 0>;

</details>

<details open>

<summary>Preview</summary>

![opentype-01](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-01.png)
![opentype-02](https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-02.png)

</details>

</details>

---

based on [Figtree](https://github.com/erikdkennedy/figtree)