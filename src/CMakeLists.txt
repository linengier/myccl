CMAKE_MINIMUM_REQUIRED(VERSION 2.8.4)
SET(CCL_TEST_SRC test.c)
INCLUDE_DIRECTORIES(/tmp/test/include)
LINK_DIRECTORIES(/tmp/test/lib)
ADD_EXECUTABLE(test ${CCL_TEST_SRC})
TARGET_LINK_LIBRARIES(test ccl.so)


