# 重用Playbook

不能站在巨人的肩膀上的编程语言不是好语言，支持重用机制会节省调研重复的工作上浪费大量的时间，当然也会提高可维护性。

Playbook的支持两种重用机制，一种是简单的直接重新利用静态的Playbook脚本，例外一种是类似于编程语言中函数的机制。

* include语句 - 重用静态的Playbook脚本，使用起来简单、直接。
* role语言 - Playbook的“函数机制”，使用方法稍复杂、功能强大。是Playbook脚本的共享平台ansible galaxy主要的分享方式。
