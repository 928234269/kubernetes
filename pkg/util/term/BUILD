load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "term.go",
        "term_writer.go",
    ],
    importpath = "k8s.io/kubernetes/pkg/util/term",
    visibility = ["//visibility:public"],
    deps = [
        "//pkg/util/interrupt:go_default_library",
        "//vendor/github.com/docker/docker/pkg/term:go_default_library",
        "//vendor/github.com/mitchellh/go-wordwrap:go_default_library",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["term_writer_test.go"],
    embed = [":go_default_library"],
)
