# 快速选择工具
## 一、介绍  
快速选择工具组包括快速选择工具和魔棒工具，前者相对于边缘，后者相对于颜色来进行快速选择。  

## 二、用法  
### 快速选择工具  
快速选择工具会自动检测出物体的边缘，选择不跨越物体边缘的部分。  
![single-quick-move](/images/select/single-quick-move.gif)  
上面的示例是单图层选择，在选项栏中可以勾选`对所有的图层取样`的选项，对所有图层进行选择。  
![all-quick-move](/images/select/all-quick-move.gif)  
> 补充：如果要剪去选区，可以按住`Alt`键后移动选择工具（鼠标）；如果要反向选择，可以按`Ctrl+Shift+i`快键键。  
### 魔棒工具  
魔棒工具会自动检测出相似的颜色，然后选择这些区域。相似度由选项栏中的容差决定。容差越低表示颜色要越相似才会被选择，反之，对颜色的相似度要求会减小。  
![continuity](/images/select/continuity-magic-wand.gif)  
上面的示例选择了选项栏中的连续选项，它的作用是对区域的选择不透过物体的边缘。如果不勾选，就选择整个画面颜色相似的区域。  
![discontinuity](/images/select/discontinuity-magic-wand.gif)

# 快捷键
1. 按住`Alt`使用选择工具，可以快速使用“从选区中减去”的功能。
2. 使用`Ctrl+Shift+i`可以对选区反选。