file (GLOB HEADERS *.h)

add_executable (ls ls.c ${HEADERS})
target_link_libraries (ls ${APUE})

add_executable (echo echo.c ${HEADERS})
target_link_libraries (echo ${APUE})

add_executable (echoc echoc.c ${HEADERS})
target_link_libraries (echoc ${APUE})

add_executable (pid pid.c ${HEADERS})
target_link_libraries (pid ${APUE})

add_executable (shell shell.c ${HEADERS})
target_link_libraries (shell ${APUE})
