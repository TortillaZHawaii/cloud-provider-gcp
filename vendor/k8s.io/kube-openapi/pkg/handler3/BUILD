load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "handler3",
    srcs = ["handler.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-openapi/pkg/handler3",
    importpath = "k8s.io/kube-openapi/pkg/handler3",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/gnostic-models/openapiv3",
        "//vendor/github.com/google/uuid",
        "//vendor/github.com/munnerz/goautoneg",
        "//vendor/google.golang.org/protobuf/proto",
        "//vendor/k8s.io/klog/v2:klog",
        "//vendor/k8s.io/kube-openapi/pkg/cached",
        "//vendor/k8s.io/kube-openapi/pkg/common",
        "//vendor/k8s.io/kube-openapi/pkg/spec3",
    ],
)
