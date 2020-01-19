load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["registry.go"],
    importmap = "k8s.io/kubernetes/vendor/github.com/Microsoft/hcsshim/internal/cni",
    importpath = "github.com/Microsoft/hcsshim/internal/cni",
    visibility = ["//vendor/github.com/Microsoft/hcsshim:__subpackages__"],
    deps = [
        "//vendor/github.com/Microsoft/hcsshim/internal/guid:go_default_library",
        "//vendor/github.com/Microsoft/hcsshim/internal/regstate:go_default_library",
    ],
)
