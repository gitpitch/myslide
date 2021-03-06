### gitpitch サンプルスライド


---
### スライド2枚目
* スライドはここ：[slide](https://gitpitch.com/Algo1970/gitpitch#)  
* 参考サイト：[gitpitch](http://paiza.hatenablog.com/entry/2017/06/22/GitHub%E3%81%A0%E3%81%91%E3%81%A7%E8%B6%85%E9%AB%98%E6%A9%9F%E8%83%BD%E3%81%AA%E3%82%B9%E3%83%A9%E3%82%A4%E3%83%89%E8%B3%87%E6%96%99%E3%81%8C%E4%BD%9C%E3%82%8C%E3%82%8B%E3%80%8CGitPitch%E3%80%8D%E3%81%AE)
* 参考サイト：[background](https://gitpitch.com/gitpitch/feature-demo/customize-image-size)

---
### スライド3枚目
- *This text will be italic*
- **This text will be bold**

---
### 下方向のスライド
reveal.jsのような下方向スライド

+++
### スライド3.1枚目
* Item 1
* Item 2
  * Item 2a
  * Item 2b  

+++
### スライド3.2枚目
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

+++
### スライド3.3枚目
* あいうえお
* **かきくけこ**
* ####さしすせそ
* 亜衣鵜絵尾
##### あいうえお

+++
### スライド3.4枚目
As Kanye West said:

> We're living the future so
> the present is our past.

---
### アニメーション表示
- AAA
- BBB |
- CCC |
- DDD |

---
### 画像表示1
<img src="/img/dog.JPG" title="dog" width="250">

+++
### 画像表示1.1
![dog](/img/dog.JPG)

---
### syntax highlighting
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

+++
### code-presenting
```python
from time import localtime

activities = {8: 'Sleeping', 9: 'Commuting', 17: 'Working',
              18: 'Commuting', 20: 'Eating', 22: 'Resting' }

time_now = localtime()
hour = time_now.tm_hour

for activity_time in sorted(activities.keys()):
    if hour < activity_time:
        print activities[activity_time]
        break
else:
    print 'Unknown, AFK or sleeping!'
```
@[1]
@[3-4]
@[6-7]
@[9-14]

+++
### table
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---
### URL
http://www.github.com/

---
### emoji

* :smile: 
* :muscle: |
* :muscle: |

---?image=img/bluesea.JPG
### <a style="color: white">background</a>
<a style="color: white">Custom size: not specified</a>
<a style="color: white">Image size defaults to 100% 100%</a>

+++?image=img/ishigaki.JPG
### <a style="color: white">background</a>
<a style="color: white">Custom size: not specified</a>
<a style="color: white">Image size defaults to 100% 100%</a>

---?image=img/ishigakijima.JPG&size=auto
### <a style="color: white">background</a>
<a style="color: white">Custom size: auto</a>

---?image=img/shigetomi.JPG&size=cover
### <a style="color: white">background</a>
<a style="color: white">Custom size: cover</a>

+++
### youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/ux7OWM28F1U" frameborder="0" allowfullscreen></iframe>

+++
### youtube
![youtube](https://www.youtube.com/embed/ux7OWM28F1U)

---?image=img/soukisoba.JPG&size=auto 90%
### <a style="color: white">background</a>
<a style="color: white">Custom size: auto 90</a>

---?image=img/bluski.JPG&size=90% 90%
### <a style="color: white">background</a>
<a style="color: white">Custom size: 90% 90%</a>

---?video=/img/ground.MOV
### <a style="color: white">movie file</a>
<figcaption><a href="https://gitpitch.com/Algo1970/gitpitch#" style="color: white">https://gitpitch.com/Algo1970/gitpitch#</a></figcaption>




