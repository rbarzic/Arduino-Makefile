BOARD_TAG    = uno
ARDUINO_LIBS =

include ../../Arduino.mk

check-syntax:
	$(CXX_NAME) -c -include Arduino.h   -x c++ $(CXXFLAGS)   $(CPPFLAGS)  -fsyntax-only $(CHK_SOURCES)
