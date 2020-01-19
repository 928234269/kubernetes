load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["import_tracker.go"],
    importpath = "k8s.io/kubernetes/cmd/libs/go2idl/go-to-protobuf/protobuf",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/gengo/namer:go_default_library",
        "//vendor/k8s.io/gengo/types:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["namer_test.go"],
    embed = [":go_default_library"],
)
