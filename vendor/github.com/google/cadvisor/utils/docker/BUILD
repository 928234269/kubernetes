load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["docker.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/google/cadvisor/utils/docker",
    importpath = "github.com/google/cadvisor/utils/docker",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/docker/docker/api/types:go_default_library"],
)
