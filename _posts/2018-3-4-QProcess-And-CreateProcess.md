---
layout: post
title: QProcess и CreateProcess
---

Столкнулся с проблемой нежелания QProcess отображать консольное окно, при этом
WinAPI CreateProcess консольное окно отображает без проблем. В результате решение было найдено и появилась небольшая программка

![_config.yml]({{ site.baseurl }}/images/QProcess_and_CreateProcess.png)

Ссылка на [github](https://github.com/korchak/Qt/tree/master/QProcess/test2).

Источники: 
[QProcess](http://doc.qt.io/qt-5/qprocess.html), [QTimer](http://doc.qt.io/qt-5/qtimer.html), [STARTUPINFO structure](https://msdn.microsoft.com/en-us/library/windows/desktop/ms686331(v=vs.85).aspx), [ShowWindow function](https://msdn.microsoft.com/en-us/library/windows/desktop/ms633548(v=vs.85).aspx), [Process Creation Flags](https://msdn.microsoft.com/en-us/library/windows/desktop/ms684863(v=vs.85).aspx)
