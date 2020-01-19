load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "scheme_builder.go",
        "types_proto.go",
    ],
    importpath = "k8s.io/kubernetes/pkg/runtime",
    visibility = ["//visibility:public"],
)

go_test(
    name = "go_default_test",
    srcs = ["swagger_doc_generator_test.go"],
    embed = [":go_default_library"],
)
