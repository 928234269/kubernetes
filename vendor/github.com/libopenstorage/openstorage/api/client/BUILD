load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "client.go",
        "request.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/libopenstorage/openstorage/api/client",
    importpath = "github.com/libopenstorage/openstorage/api/client",
    visibility = ["//visibility:public"],
)
