file (GLOB HEADERS *.h)

add_executable (ls ls.c ${HEADERS})
target_link_libraries (ls ${APUE})

add_executable (echo echo.c ${HEADERS})
target_link_libraries (echo ${APUE})

