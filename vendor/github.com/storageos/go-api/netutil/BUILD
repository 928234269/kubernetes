load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "errors.go",
        "netutil.go",
        "parsers.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/storageos/go-api/netutil",
    importpath = "github.com/storageos/go-api/netutil",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/storageos/go-api/serror:go_default_library"],
)
