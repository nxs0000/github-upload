cmake_minimum_required(VERSION 2.8)

project( test_git )


SET(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} "-std=c++17 -pthread")
set(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -Wall")
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -Wall")




set(SRCS main.cpp )
#set(HEADERS .hpp )




add_executable( test_git ${SRCS} )
#target_link_libraries( test_git   )