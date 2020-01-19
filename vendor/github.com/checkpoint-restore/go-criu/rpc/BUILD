load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["rpc.pb.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/checkpoint-restore/go-criu/rpc",
    importpath = "github.com/checkpoint-restore/go-criu/rpc",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/golang/protobuf/proto:go_default_library"],
)
