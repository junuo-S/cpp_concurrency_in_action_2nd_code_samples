project(cpp_concurrency_in_action_2nd_code_samples)

aux_source_directory(./listings/ DIR_SRCS)

add_executable(cpp_concurrency_in_action_2nd_code_samples ${DIR_SRCS})