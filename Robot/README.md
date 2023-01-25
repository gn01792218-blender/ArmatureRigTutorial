# 製作機器人Rig採坑紀錄
## 手指擺pose影響到不該影響的Mesh
莫名原因，小指頭某些指節就是會影響右側臀部的mesh<br>
最後進入weight paint模式中，將該些指節使用substract筆刷，清除weight影響<br>
```
//如何進入weight paint模式
1.到Object模式中，先選擇Armature,後選Mesh
2.點擊右上角，切換到weight模式，開始一一檢查
```