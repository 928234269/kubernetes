load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "client.go",
        "doc.go",
        "util.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/clusterhq/flocker-go",
    importpath = "github.com/clusterhq/flocker-go",
    visibility = ["//visibility:public"],
)
