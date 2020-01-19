load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "leader.go",
        "queue.go",
        "server.go",
        "stats.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/go.etcd.io/etcd/etcdserver/api/v2stats",
    importpath = "go.etcd.io/etcd/etcdserver/api/v2stats",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/coreos/pkg/capnslog:go_default_library",
        "//vendor/go.etcd.io/etcd/raft:go_default_library",
    ],
)
