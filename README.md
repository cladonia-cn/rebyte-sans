<picture>
  <source width="357" media="(prefers-color-scheme: dark)" srcset="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-dark.png">
  <source width="357" media="(prefers-color-scheme: light)" srcset="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-light.png">
  <img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/title-normal.png">
</picture>

<div>
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/preview-01.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/preview-02.png">
</div>

---

> [!NOTE]
> 这是一款使用 Figtree[^1] 作为母板来设计的字体。

<details>

<summary>
( 相较于 Figtree ) 新增的 OpenType 特性
</summary>

## Liga
##### 替换
<details>

<summary>
GSUB Features
</summary>

``` shell
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
```

</details>

<details open>

<summary>
Preview
</summary>

<div>
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-03.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-04.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-05.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-06.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-07.png">
</div>

</details>

---
## Kern
##### 间距
<details>

<summary>
GSUB Features
</summary>

``` shell
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
```

</details>

<details open>

<summary>Preview</summary>

<div>
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-01.png">
<img width="357" src="https://github.com/cladonia-cn/rebyte-sans/blob/pro/documentation/opentype-02.png">
</div>

</details>

</details>

<details>
  <summary>支持的字符</summary>

<table style="undefined;table-layout: fixed; width: 835px">
<colgroup>
<col style="width: 32px">
<col style="width: 71px">
<col style="width: 122px">
<col style="width: 122px">
<col style="width: 122px">
<col style="width: 122px">
<col style="width: 122px">
<col style="width: 122px">
</colgroup>
<thead>
  <tr>
    <th></th>
    <th>类别</th>
    <th colspan="6">字符</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td rowspan="6">符号</td>
    <td>! (exclam)</td>
    <td>' (quotesingle)</td>
    <td>" (quotedbl)</td>
    <td># (numbersign)</td>
    <td>~ (asciitilde)</td>
    <td>% (percent)</td>
  </tr>
  <tr>
    <td>2</td>
    <td>( [parenleft]</td>
    <td>) [parenright]</td>
    <td>+ (plus)</td>
    <td>- (hyphenminus)</td>
    <td>&amp; (ampersand)</td>
    <td>. (period)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>/ (slash)</td>
    <td>\ (backslash)</td>
    <td>: (colon)</td>
    <td>; (semicolon)</td>
    <td>&lt; (less)</td>
    <td>&gt; (greater)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>= (equal)</td>
    <td>? (question)</td>
    <td>@ (at)</td>
    <td>[ (bracketleft)</td>
    <td>] (bracketright)</td>
    <td>^ (asciicircum)</td>
  </tr>
  <tr>
    <td>5</td>
    <td>_ (underscore)</td>
    <td>` (grave)</td>
    <td>{ (braceleft)</td>
    <td>} (braceright)</td>
    <td>© (copyright)</td>
    <td>® (registered)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>TM (trademark)</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>7</td>
    <td rowspan="2">数字</td>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
  </tr>
  <tr>
    <td>8</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
    <td>0</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>9</td>
    <td rowspan="5">大写字母</td>
    <td>A</td>
    <td>B</td>
    <td>C</td>
    <td>D</td>
    <td>E</td>
    <td>F</td>
  </tr>
  <tr>
    <td>10</td>
    <td>G</td>
    <td>H</td>
    <td>I</td>
    <td>J</td>
    <td>K</td>
    <td>L</td>
  </tr>
  <tr>
    <td>11</td>
    <td>M</td>
    <td>N</td>
    <td>O</td>
    <td>P</td>
    <td>Q</td>
    <td>R</td>
  </tr>
  <tr>
    <td>12</td>
    <td>S</td>
    <td>T</td>
    <td>U</td>
    <td>V</td>
    <td>W</td>
    <td>X</td>
  </tr>
  <tr>
    <td>13</td>
    <td>Y</td>
    <td>Z</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>14</td>
    <td rowspan="5">小写字母</td>
    <td>a</td>
    <td>b</td>
    <td>c</td>
    <td>d</td>
    <td>e</td>
    <td>f</td>
  </tr>
  <tr>
    <td>15</td>
    <td>g</td>
    <td>h</td>
    <td>i</td>
    <td>j</td>
    <td>k</td>
    <td>l</td>
  </tr>
  <tr>
    <td>16</td>
    <td>m</td>
    <td>n</td>
    <td>o</td>
    <td>p</td>
    <td>q</td>
    <td>r</td>
  </tr>
  <tr>
    <td>17</td>
    <td>s</td>
    <td>t</td>
    <td>u</td>
    <td>v</td>
    <td>w</td>
    <td>x</td>
  </tr>
  <tr>
    <td>18</td>
    <td>y</td>
    <td>z</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>货币</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td colspan="7">...还有其他的字母、数字和符号变体</td>
  </tr>
</tbody>
</table>

</details>

---

[^1]: 本字体并非完全由 Cladonia 设计师设计的，而是基于 [@Erikdkennedy](https://github.com/erikdkennedy/) 设计的 [Figtree](https://github.com/erikdkennedy/figtree) 字体来修改的。感谢 [@Erikdkennedy](https://github.com/erikdkennedy/)
