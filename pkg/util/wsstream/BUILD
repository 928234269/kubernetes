load("@io_bazel_rules_go//go:def.bzl", "go_test")

go_test(
    name = "go_default_test",
    srcs = [
        "conn_test.go",
        "stream_test.go",
    ],
    deps = ["//vendor/golang.org/x/net/websocket:go_default_library"],
)
