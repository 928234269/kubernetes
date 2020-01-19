load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["monitoring-gen.go"],
    importmap = "k8s.io/kubernetes/vendor/google.golang.org/api/monitoring/v3",
    importpath = "google.golang.org/api/monitoring/v3",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/api/gensupport:go_default_library",
        "//vendor/google.golang.org/api/googleapi:go_default_library",
        "//vendor/google.golang.org/api/option:go_default_library",
        "//vendor/google.golang.org/api/transport/http:go_default_library",
    ],
)
