load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "historical_types.go",
        "model_types.go",
        "types.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/heapster/metrics/api/v1/types",
    importpath = "k8s.io/heapster/metrics/api/v1/types",
    visibility = ["//visibility:public"],
)
