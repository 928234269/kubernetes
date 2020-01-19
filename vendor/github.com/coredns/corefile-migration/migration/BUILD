load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "migrate.go",
        "notice.go",
        "versions.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/coredns/corefile-migration/migration",
    importpath = "github.com/coredns/corefile-migration/migration",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/coredns/corefile-migration/migration/corefile:go_default_library"],
)
