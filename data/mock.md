流程图
```flow
st=>start: 陪妹子进商场
op=>operation: 买买买
cond=>condition: 妹子开不开心?
e=>end: 出商场
st->op->cond
cond(yes)->e
cond(no)->op
```
序列图
```sequence
战士->领导: 首长好
Note right of 领导: 首长复杂的内心活动
领导-->战士: 同志们好
战士->>领导: 为人民服务
```
mermaid甘特图
```mermaid
gantt
title 甘特图
dateFormat YYYY-MM-DD
section 行1
任务1 :a1, 2014-01-01, 30d
任务2 :after a1 , 20d
section 行2
任务3 :2014-01-12 , 12d
任务4 : 24d
```
