# Required to generate MOC
target_sources(
  flameshot
  PRIVATE buttonhandler.h
          capturebutton.h
          capturewidget.h
          colorpicker.h
          hovereventfilter.h
          selectionwidget.h
          notifierbox.h)

target_sources(
  flameshot
  PRIVATE buttonhandler.cpp
          capturebutton.cpp
          capturewidget.cpp
          colorpicker.cpp
          hovereventfilter.cpp
          modificationcommand.cpp
          notifierbox.cpp
          selectionwidget.cpp)
