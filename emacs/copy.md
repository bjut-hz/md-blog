# emacs 复制一个文本区域到另一个地方：

1. 把光标移动到区域的首字符
2. 键入C-@（即ctrl+shift+2）,以设置标记
3. 把光标移动到区域的最后一个字符
4. 键入M-w，拷贝这个选定区域到粘贴板（剪切是C-w）
5. 用光标定位将要粘贴内容的地方，然后键入C-y ，拷贝成功。