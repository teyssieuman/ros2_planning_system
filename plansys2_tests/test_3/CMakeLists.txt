install(DIRECTORY pddl
  DESTINATION share/${PROJECT_NAME}/test_3
)

ament_add_gtest(test_3 test_3.cpp)
target_link_libraries(test_3 ${PROJECT_NAME})
