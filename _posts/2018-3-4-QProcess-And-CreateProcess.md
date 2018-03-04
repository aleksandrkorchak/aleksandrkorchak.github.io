---
layout: post
title: QProcess и CreateProcess
---

Столкнулся с проблемой нежелания QProcess отображать консольное окно, при этом
WinAPI CreateProcess консольное окно отображает без проблем. В результате решение было найдено и появилась небольшая программка

![_config.yml]({{ site.baseurl }}/images/QProcess_and_CreateProcess.png)

Ссылка на [github](https://github.com/korchak/Qt/tree/master/QProcess/test2).

Источники: 
[QProcess](http://doc.qt.io/qt-5/qprocess.html), [QTimer](http://doc.qt.io/qt-5/qtimer.html)
