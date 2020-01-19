load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["cache.go"],
    importpath = "k8s.io/kubernetes/pkg/util/cache",
    visibility = ["//visibility:public"],
)

go_test(
    name = "go_default_test",
    srcs = ["cache_test.go"],
    embed = [":go_default_library"],
)
