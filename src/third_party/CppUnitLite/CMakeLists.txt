project(CppUnitLite)
FILE(GLOB CppUnitLite_SRC "*.h" "*.cpp")
ADD_LIBRARY(CppUnitLite ${CppUnitLite_SRC})
SET_TARGET_PROPERTIES(CppUnitLite PROPERTIES LINKER_LANGUAGE CXX)
