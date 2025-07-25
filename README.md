绝大多数人都有写简历的需要，利用 Obsidian 写简历有几个优势

1. 本地简历，尽可能的减少自己个人隐私的泄漏。
2. 无需调整格式，直接撰写内容就可以。
3. 不会有任何广告的搔扰
4. 可以保存无数份简历，也方便简历间内容的相互引用。
5. **通过属性控制样式，不会影响 Obsidian 本身的使用。**
6. 可以方便的导出 pdf 
7. 以及 Obsidian 本身所拥有的所有优点

# 使用效果

<img width="3040" height="1899" alt="Pasted image 20250719115525" src="https://github.com/user-attachments/assets/b8ef008a-aa4b-4f9f-bb7e-04f46b9ffc0e" />


# 使用指引

对于没有使用 Obsidian 经验的同学，建议将简历模板复制一份，然后直接在模板上进行修改。


# 简历效果实现的要点

对于想将效果应用到自己的 Obsidian 库中的同学使用
## 1、理解css文件

之所以可以实现简历样式，是通过css 样式文件控制的。所以第一件事，就是找到css文件，并放入到正确位置。

<img width="1871" height="1662" alt="Pasted image 20250719115133" src="https://github.com/user-attachments/assets/c9735d7e-34ea-4cd5-9046-914168ec4ba4" />


按图，点击文件夹图标，然后将 css文件放入该文件夹，然后回到这个页面，点击刷新图标，然后开启这个文件。


## 2、指定对特定笔记生效


1、新建笔记时，需要在笔记属性中 指定值： `cssclasses: cv`


## 3、使用阅读视图查看效果

在左侧使用编辑模式，右侧使用阅读模式查看效果。
在 Obsidian 中，使用 左右分屏即可实现这样的效果。

<img width="3040" height="1899" alt="Pasted image 20250719115525" src="https://github.com/user-attachments/assets/b8ef008a-aa4b-4f9f-bb7e-04f46b9ffc0e" />


# 感谢

本项目在该项目的基础上进行的更改和调整
https://github.com/BingyanStudio/LapisCV?tab=readme-ov-file
