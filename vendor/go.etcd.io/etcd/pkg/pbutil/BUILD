load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["pbutil.go"],
    importmap = "k8s.io/kubernetes/vendor/go.etcd.io/etcd/pkg/pbutil",
    importpath = "go.etcd.io/etcd/pkg/pbutil",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/coreos/pkg/capnslog:go_default_library"],
)
