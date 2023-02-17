---
layout: post
title: 使用GitHub Pages创建博客
---

Jekyll的主要功能是将静态文件转换为静态网站。
比如在本地某个空目录下执行```jekyll new myblog```之后，该目录下就会生成构建静态网站的必要文件:

![Alt text](https://g.gravizo.com/source/custom_mark21?https%3A%2F%2Fraw.githubusercontent.com%2FTLmaK0%2Fgravizo%2Fmaster%2FREADME.md)

<details> 
<summary></summary>
custom_mark21	
@startuml
start
:init;
-> test of color;
if (color?) is (<color:red>red) then
:print red;
else 
:print not red;
note right: no color
endif
partition End {
:end;
}
-> this is the end;
end
@enduml
custom_mark21
</details>