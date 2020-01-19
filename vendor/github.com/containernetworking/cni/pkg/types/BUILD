load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "args.go",
        "types.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/containernetworking/cni/pkg/types",
    importpath = "github.com/containernetworking/cni/pkg/types",
    visibility = ["//visibility:public"],
)
