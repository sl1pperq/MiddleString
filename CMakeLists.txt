cmake_minimum_required(VERSION 3.26)
project(MiddleString)

set(CMAKE_CXX_STANDARD 17)

add_executable(MiddleString main.cpp
        itc_1_isDigit.cpp
        middle_str.h
        itc_2_toUpper.cpp
        itc_4_compare.cpp
        itc_3_changeCase.cpp
        itc_5_countWords.cpp
        itc_6_maxCharWord.cpp
        itc_7_sameChar.cpp
        itc_8_isFirstInSecond.cpp
        itc_9_Cezar.cpp
        itc_10_rmFreeSpace.cpp
        itc_11_isIp.cpp)
