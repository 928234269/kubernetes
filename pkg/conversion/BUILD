load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["helper.go"],
    importpath = "k8s.io/kubernetes/pkg/conversion",
    visibility = ["//visibility:public"],
)

go_test(
    name = "go_default_test",
    srcs = ["helper_test.go"],
    embed = [":go_default_library"],
)
