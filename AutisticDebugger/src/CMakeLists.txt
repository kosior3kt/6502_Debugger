set(SOURCES
   main.cpp
)


add_executable(dbg
   ${SOURCES}
   )

target_include_directories(
   dbg
   PUBLIC
   ${INC}
   #${COMMON_INC}
)


