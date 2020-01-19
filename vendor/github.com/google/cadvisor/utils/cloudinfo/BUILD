load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["cloudinfo.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/google/cadvisor/utils/cloudinfo",
    importpath = "github.com/google/cadvisor/utils/cloudinfo",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cadvisor/info/v1:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
    ],
)
