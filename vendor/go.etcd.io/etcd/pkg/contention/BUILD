load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "contention.go",
        "doc.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/go.etcd.io/etcd/pkg/contention",
    importpath = "go.etcd.io/etcd/pkg/contention",
    visibility = ["//visibility:public"],
)
