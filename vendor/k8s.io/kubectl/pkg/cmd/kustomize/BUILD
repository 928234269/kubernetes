load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["kustomize.go"],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/kubectl/pkg/cmd/kustomize",
    importpath = "k8s.io/kubectl/pkg/cmd/kustomize",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/spf13/cobra:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/genericclioptions:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/kustomize:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/i18n:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/templates:go_default_library",
        "//vendor/sigs.k8s.io/kustomize/pkg/fs:go_default_library",
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
