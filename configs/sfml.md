## SFML Development .pro file
```sh
TEMPLATE = app
CONFIG += console c++11
CONFIG -= app_bundle
CONFIG -= qt
INCLUDEPATH += D:\lib\sfml\include
SOURCES += \
        main.cpp

DISTFILES += \
    images/background.png \
    images/frame.png \
    images/tiles.png

LIBS += D:\lib\sfml\bin\openal32.dll
LIBS += D:\lib\sfml\bin\sfml-audio-2.dll
LIBS += D:\lib\sfml\bin\sfml-audio-d-2.dll
LIBS += D:\lib\sfml\bin\sfml-graphics-2.dll
LIBS += D:\lib\sfml\bin\sfml-graphics-d-2.dll
LIBS += D:\lib\sfml\bin\sfml-network-2.dll
LIBS += D:\lib\sfml\bin\sfml-network-d-2.dll
LIBS += D:\lib\sfml\bin\sfml-system-2.dll
LIBS += D:\lib\sfml\bin\sfml-system-d-2.dll
LIBS += D:\lib\sfml\bin\sfml-window-2.dll
LIBS += D:\lib\sfml\bin\sfml-window-d-2.dll

LIBS += -LD:\lib\sfml\lib \
    -lFLAC
    -lfreetype
    -logg
    -lopenal32
    -lsfml-audio-d
    -lsfml-audio-s-d
    -lsfml-audio-s
    -lsfml-audio
    -lsfml-graphics-d
    -lsfml-graphics-s-d
    -lsfml-graphics-s
    -lsfml-graphics
    -lsfml-main-d
    -lsfml-main
    -lsfml-network-d
    -lsfml-network-s-d
    -lsfml-network-s
    -lsfml-network
    -lsfml-system-d
    -lsfml-system-s-d
    -lsfml-system-s
    -lsfml-system
    -lsfml-window-d
    -lsfml-window-s-d
    -lsfml-window-s
    -lsfml-window
    -lvorbis
    -lvorbisenc
    -lvorbisfile
```
