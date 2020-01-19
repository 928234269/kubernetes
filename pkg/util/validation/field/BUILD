load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = ["path.go"],
    importpath = "k8s.io/kubernetes/pkg/util/validation/field",
    visibility = ["//visibility:public"],
)

go_test(
    name = "go_default_test",
    srcs = ["path_test.go"],
    embed = [":go_default_library"],
)
