load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "delete.go",
        "delete_flags.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/kubectl/pkg/cmd/delete",
    importpath = "k8s.io/kubectl/pkg/cmd/delete",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/spf13/cobra:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/meta:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/genericclioptions:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/printers:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/resource:go_default_library",
        "//vendor/k8s.io/client-go/dynamic:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/cmd/util:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/cmd/wait:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/rawhttp:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/i18n:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/templates:go_default_library",
    ],
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
