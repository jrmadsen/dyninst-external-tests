project(dataflowAPI)

add_executable(df_insertion_operators insertion_operators.cpp)
set_target_properties(df_insertion_operators PROPERTIES OUTPUT_NAME insertion_operators)
target_include_directories(df_insertion_operators PRIVATE ${DYNINST_INCLUDE_DIR} ${Boost_INCLUDE_DIR})
