load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "escape.go",
        "line_delimiter.go",
        "strings.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/utils/strings",
    importpath = "k8s.io/utils/strings",
    visibility = ["//visibility:public"],
)
