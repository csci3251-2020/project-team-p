# Introduction

| Things we will do             |
| ------------------------------|
|1.Starting issues              |
|2.Project board                |
|3.Set up readme.md             |
|4.Show our team to the Internet|
|5.Keep checking...             |
|6.Write C code                 |
|7.Get a status badge           |
|8.Promote our repo             |

# Code
```c
#include <stdio.h>

int main(){
  printf("Hello world);
  return 0;
}
```

# Contributors
<ul>
{% for member in site.stu -%}
  <li>
  <p> <img src="{{member.image}}" width="50" height="50"> @ {{ member.user }}({{ member.name }})
    <ul><li>{{member.content | markdownify}}</li></ul>
  </p>
  </li>
{%- endfor -%}
</ul>


| Issue |People      |
|:-----:|------------|
| 1     |CHANG,Chirui|
| 2     |Tsoi Chak Yu|
| 3     |KUANG, Yurui|
| 4     |TO, Ka Ho   |
| 5     |Leung Kong Wai|
| 6     |Yeung Cheung Nam|
| 7     |TONG Kai Tik|
| 8     |Yu Ka Wai     |

---
Last updated: {{ site.time }}
