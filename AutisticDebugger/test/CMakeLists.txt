set (TEST_SOURCES
   main.cpp
   test.hpp
   )

set (TEST_SOURCES_DEBUG
   main.cpp
   test.hpp
   )


if(ALTERNATIVE)
   add_executable(test_dbg
      ${TEST_SOURCES_DEBUG}
      )
   #add_compile_definitions(ALTERNATIVE)

else()
   add_executable(test_dbg
      ${TEST_SOURCES}
      )

endif()

find_package(GTest CONFIG REQUIRED)


target_link_libraries(test_dbg
   #CPU
   GTest::gtest
   )



