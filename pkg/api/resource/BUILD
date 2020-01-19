load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "amount.go",
        "quantity_proto.go",
        "scale_int.go",
        "suffix.go",
    ],
    importpath = "k8s.io/kubernetes/pkg/api/resource",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/gogo/protobuf/proto:go_default_library",
        "//vendor/gopkg.in/inf.v0:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["math_test.go"],
    embed = [":go_default_library"],
)
