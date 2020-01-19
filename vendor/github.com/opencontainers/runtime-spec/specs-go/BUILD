load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "config.go",
        "state.go",
        "version.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/opencontainers/runtime-spec/specs-go",
    importpath = "github.com/opencontainers/runtime-spec/specs-go",
    visibility = ["//visibility:public"],
)
