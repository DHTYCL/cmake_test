cmake_minimum_required(VERSION 2.8)

project(sticker_me)
include_directories(/home/aitian/project/cmake_test/fun/fun.h)
aux_source_directory(. src_dir)
add_executable(sticker_me ${src_dir})

target_link_libraries(sticker_me /home/aitian/project/cmake_test/fun/libutils.so )
