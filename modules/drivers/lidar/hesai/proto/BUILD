## Auto generated by `proto_build_generator.py`
load("@rules_proto//proto:defs.bzl", "proto_library")
load("@rules_cc//cc:defs.bzl", "cc_proto_library")
load("//tools:python_rules.bzl", "py_proto_library")

package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "config_cc_proto",
    deps = [
        ":config_proto",
    ],
)

proto_library(
    name = "config_proto",
    srcs = ["config.proto"],
    deps = [
        ":hesai_proto",
    ],
)

py_proto_library(
    name = "config_py_pb2",
    deps = [
        ":config_proto",
        ":hesai_py_pb2",
    ],
)

cc_proto_library(
    name = "hesai_cc_proto",
    deps = [
        ":hesai_proto",
    ],
)

proto_library(
    name = "hesai_proto",
    srcs = ["hesai.proto"],
    deps = [
        "//modules/common/proto:header_proto",
    ],
)

py_proto_library(
    name = "hesai_py_pb2",
    deps = [
        ":hesai_proto",
        "//modules/common/proto:header_py_pb2",
    ],
)
