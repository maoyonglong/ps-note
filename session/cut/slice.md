# 切片工具  

## 介绍  
切片工具包括切片工具和切片选择工具，前者用于切片，后者用于选择切片。   

## 切片工具
### 创建切片的方式   
切片的创建方式有两种，分别是直接拖动鼠标拉出方框和使用参考线进行切片。  
1. 拖动鼠标创建：  
![slice-create-move](/images/cut/slice-create-move.gif)  
2. 使用参考线创建：  
![slice-create-refer](/images/cut/slice-create-refer.gif)   
### 选项  
* 样式  
样式选项可以选择固定切片的宽高比或者大小。  

## 切片选择工具  
切片选择工具用于选中当前切片。选中切片使用右键会出现一个右键菜单，置于`*`层的选项用于切片重叠时确定层级。  
![slice-select-move](/images/cut/slice-select-move.gif)   
可以发现右键菜单中有个划分、编辑切片选项、提升到用户切片和组合切片的选项。  
* 划分  
终于对选中切片进行再次划分。  
* 编辑切片选项  
点击后会弹出以下菜单，用来确定切片的属性。  
![slice-property](/images/cut/slice-property.jpg)   
上面的属性和html中的img标签保持一致。   
* 组合切片  
组合切片就是把选中的多个切片合并，选中多个切片的方法是按照`Shift`键依次点击切片。   
* 提升到用户切片  
在使用切片工具时，除了用户划分的切片外，软件会自动划分剩余的部分，这些自动划分的切片是自动切片。  
![slice-user-auto](/images/cut/slice-user-auto.gif)  
> 提示：以上选项在右键菜单和选项栏都可以找到。  
* 对齐  
选中多个切片时，可以使用选项栏中间的对齐方式进行对齐。   
![slice-align](/images/cut/slice-align.gif)   

## 快捷键  
1. 按住`Shift`键，依次点击切片可以同时选中多个切片。
2. 按`Ctrl+R`，可以快速显示标尺。  