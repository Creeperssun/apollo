cc_library(
    name = "hello_great",
    srcs = ["hello_great.cc"],
    hdrs = ["hello_great.h"],
    visibility = ["//demo_main:__pkg__"],
)

cc_binary(
    name = "hello_world_lib",
    srcs = ["hello_world.cc"],
    deps = [":hello_great"],
)