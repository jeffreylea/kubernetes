load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/code-generator/_examples/apiserver/informers/externalversions/example3.io",
    importpath = "k8s.io/code-generator/_examples/apiserver/informers/externalversions/example3.io",
    visibility = ["//visibility:public"],
    deps = [
        "//staging/src/k8s.io/code-generator/_examples/apiserver/informers/externalversions/example3.io/v1:go_default_library",
        "//staging/src/k8s.io/code-generator/_examples/apiserver/informers/externalversions/internalinterfaces:go_default_library",
    ],
)
