load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "bodystring.go",
        "jsonutils.go",
        "statusgroup.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/heketi/heketi/pkg/utils",
    importpath = "github.com/heketi/heketi/pkg/utils",
    visibility = ["//visibility:public"],
)
