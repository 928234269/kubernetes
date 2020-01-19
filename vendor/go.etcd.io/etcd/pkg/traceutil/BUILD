load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["trace.go"],
    importmap = "k8s.io/kubernetes/vendor/go.etcd.io/etcd/pkg/traceutil",
    importpath = "go.etcd.io/etcd/pkg/traceutil",
    visibility = ["//visibility:public"],
    deps = ["//vendor/go.uber.org/zap:go_default_library"],
)
