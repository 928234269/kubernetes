load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "handler.go",
        "helpers.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/google/cadvisor/container/libcontainer",
    importpath = "github.com/google/cadvisor/container/libcontainer",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cadvisor/container:go_default_library",
        "//vendor/github.com/google/cadvisor/info/v1:go_default_library",
        "//vendor/github.com/opencontainers/runc/libcontainer:go_default_library",
        "//vendor/github.com/opencontainers/runc/libcontainer/cgroups:go_default_library",
        "//vendor/golang.org/x/sys/unix:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
    ],
)
