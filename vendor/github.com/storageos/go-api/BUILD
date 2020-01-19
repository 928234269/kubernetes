load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "client.go",
        "health.go",
        "logger.go",
        "login.go",
        "namespace.go",
        "network_diagnostics.go",
        "node.go",
        "policy.go",
        "pool.go",
        "rule.go",
        "server_version.go",
        "template.go",
        "user.go",
        "util.go",
        "validation.go",
        "volume.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/github.com/storageos/go-api",
    importpath = "github.com/storageos/go-api",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/storageos/go-api/netutil:go_default_library",
        "//vendor/github.com/storageos/go-api/serror:go_default_library",
        "//vendor/github.com/storageos/go-api/types:go_default_library",
    ],
)
