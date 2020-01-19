load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["jws.go"],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/cluster-bootstrap/token/jws",
    importpath = "k8s.io/cluster-bootstrap/token/jws",
    visibility = ["//visibility:public"],
    deps = ["//vendor/gopkg.in/square/go-jose.v2:go_default_library"],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
