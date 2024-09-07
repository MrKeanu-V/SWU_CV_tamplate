Made by GitHub @MrKeanu

一、版权与字体
本模板使用的字体为开源字体狮尾四季春，详见
https://github.com/max32002/swei-spring

二、致谢
本模板基于
1. 武大中文CV模板：https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd
2. 西北工业大学中文CV模板：https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx

此模板的改动有：
1. 修改校标、配色、字体等；
2. 增加研究生对应模块；
3. 做了一些更契合个人习惯的改动（毕竟是自用模板）
4. 在header和footer添加了西大的视觉系统元素

三、使用方法
使用XeLaTeX编译。建议上传Overleaf编译。

四、其他注意事项
1. 所有以\fa开头的都是font awesome宏包里的logo。详细信息参考：
https://mirrors.ibiblio.org/CTAN/fonts/fontawesome5/doc/fontawesome5.pdf
2. 如何修改栏目名称？以个人信息为例。
本模板中使用下述命令定义栏目名（即章节名）
\section{\makebox[\widthof{\faAddressCard}][c]{\color{WHU_Blue}{\faAddressCard}}\quad 个人信息}
\faAddressCard为图标，前面有人提到。个人信息即章节名。其他如无必要可以不用管。
3. 我注释掉了一些我用不到的东西。如果你觉得有用，可以选中后按ctrl+/取消注释。
4. 如有修改建议，请到 github 页面提交 issue： https://github.com/MrKeanu-V/SWU_CV_tamplate