set(SRCS app.main.cpp)

add_executable(app ${SRCS})
target_link_libraries(app PRIVATE hello)

add_test(NAME smoke_test COMMAND app)
