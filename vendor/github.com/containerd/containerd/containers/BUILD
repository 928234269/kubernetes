load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["containers.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/containerd/containerd/containers",
    importpath = "github.com/containerd/containerd/containers",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/gogo/protobuf/types:go_default_library"],
)
