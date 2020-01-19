load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["install.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/google/cadvisor/container/systemd/install",
    importpath = "github.com/google/cadvisor/container/systemd/install",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cadvisor/container:go_default_library",
        "//vendor/github.com/google/cadvisor/container/systemd:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
    ],
)
