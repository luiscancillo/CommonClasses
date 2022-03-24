cmake_minimum_required(VERSION 3.21)
project(CommonClasses)

set(CMAKE_CXX_STANDARD 11)

add_library(CommonClasses RinexData.h RinexData.cpp ArgParser.h ArgParser.cpp GNSSdataFromOSP.h GNSSdataFromOSP.cpp Logger.h Logger.cpp OSPMessage.h OSPMessage.cpp RTKobservation.h RTKobservation.cpp Utilities.h Utilities.cpp)
