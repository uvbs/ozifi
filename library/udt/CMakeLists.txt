add_library (udtlib server.cpp client.cpp event_queue.cpp)
target_link_libraries(udtlib utils
                             udt4
                             ${Boost_LIBRARIES})
