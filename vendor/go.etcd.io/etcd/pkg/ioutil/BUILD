load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "pagewriter.go",
        "readcloser.go",
        "reader.go",
        "util.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/go.etcd.io/etcd/pkg/ioutil",
    importpath = "go.etcd.io/etcd/pkg/ioutil",
    visibility = ["//visibility:public"],
    deps = ["//vendor/go.etcd.io/etcd/pkg/fileutil:go_default_library"],
)
