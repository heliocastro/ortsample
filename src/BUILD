load("@rules_cc//cc:defs.bzl", "cc_library")

cc_binary(
    name = "prjtest",
    srcs = [ "projtest.cpp" ],
    deps = [ ":iamboost" ],
    visibility = ["//main:__pkg__"],
    linkopts = [ "-lproj" ],
)

cc_library(
    name = "iamboost",
    srcs = [ "iamboost.cpp" ],
    hdrs = [ "iamboost.h" ],
    linkopts = [ "-lboost_locale" ],
    visibility = ["//main:__pkg__"],
)
