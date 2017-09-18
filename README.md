
# fidding emacs配置
个人的spacemacs layer配置 , 开发堆栈(php+html+css+js)

## 安装

1. 安装emacs

 https://www.gnu.org/software/emacs/download.html

2. 安装spacemacs
```
cd /
git clone https://github.com/syl20bnr/spacemacs.git ~/.emacs.d
```
3. 安装我的配置
```
cd /
git clone https://github.com/fidding/spacemacs.d.git ~/spacemacs.d
```

## 如何配置

安装完成之后，打开你的.spacemacs文件。

1. 添加配置路径
```
dotspacemacs-configuration-layer-path '("~/spacemacs.d/")
```
2. 引用配置
```
dotspacemacs-configuration-layers '(fidding）
```

## 都有什么
**插件**

1. dracula-theme主题

2. cpmpany自动补全

3. nyan-cat彩虹猫

4. web-mode

5. php-mode

6. php-extras php函数提示 , 需要执行(M-x php-extras-generate-eldoc)

7. idle-highlight-mode选中词匹配高亮

8. magit git版本控制


**基本配置**

1. 自定义窗口标题

2. 初始窗口最大化

3. 显示行号

4. 保存buffer时移除多余空格

5. php环境开发

***
**将持续更新，欢迎star&fork!!**
# happy joining！
