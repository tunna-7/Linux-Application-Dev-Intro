## HOW TO RUN?

1. qmake SimpleQtApp.pro
2. make
3. ./SimpleQtApp (if there are no issues)
4. QT_DEBUG_PLUGINS=1 ./SimpleQtApp


## ERRORS FACED DURING EXECUTION
1. Make sure you SimpleQtApp.pro file is correct
2. ./SimpleQtApp gives out qt.qpa.plugin: Could not find the Qt platform plugin "wayland" in ""
./SimpleQtApp: symbol lookup error: /snap/core20/current/lib/x86_64-linux-gnu/libpthread.so.0: undefined symbol: __libc_pthread_init, version GLIBC_PRIVATE

    Solution:
    1. Try ./SimpleQtApp -platform xcb, if it gives some error
    2. Run sudo apt install libqt5gui5 libqt5core5a libxcb-xinerama0



# FINAL UI

![image](https://github.com/user-attachments/assets/9f8c8986-b36b-49ac-8409-f3da6256dd9e)
