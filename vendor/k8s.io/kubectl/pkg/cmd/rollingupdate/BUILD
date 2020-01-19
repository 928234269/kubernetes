load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "rolling_updater.go",
        "rollingupdate.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/kubectl/pkg/cmd/rollingupdate",
    importpath = "k8s.io/kubectl/pkg/cmd/rollingupdate",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/spf13/cobra:go_default_library",
        "//vendor/k8s.io/api/core/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/labels:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/intstr:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/genericclioptions:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/printers:go_default_library",
        "//vendor/k8s.io/cli-runtime/pkg/resource:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/core/v1:go_default_library",
        "//vendor/k8s.io/client-go/scale:go_default_library",
        "//vendor/k8s.io/client-go/util/retry:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/cmd/util:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/scale:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/scheme:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/deployment:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/i18n:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/podutils:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/util/templates:go_default_library",
        "//vendor/k8s.io/kubectl/pkg/validation:go_default_library",
        "//vendor/k8s.io/utils/integer:go_default_library",
        "//vendor/k8s.io/utils/pointer:go_default_library",
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
