load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")
load("//tools/install:install.bzl", "install", "install_src_files")
load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_binary(
    name = "talker",
    srcs = ["talker.cc"],
    deps = [
        "//cyber",
        "//cyber/abc_study_ws/sf_ws/second/proto:car_msg_cc_proto",
    ],
    linkstatic = True,
)

cc_binary(
    name = "listener",
    srcs = ["listener.cc"],
    deps = [
        "//cyber",
        "//cyber/abc_study_ws/sf_ws/second/proto:car_msg_cc_proto",
    ],
    linkstatic = True,
)