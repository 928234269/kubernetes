load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["etcd_util.go"],
    importpath = "k8s.io/kubernetes/pkg/storage/etcd/util",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/coreos/etcd/client:go_default_library"],
)
