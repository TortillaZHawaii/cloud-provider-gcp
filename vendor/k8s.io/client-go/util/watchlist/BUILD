load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "watchlist",
    srcs = ["watch_list.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/util/watchlist",
    importpath = "k8s.io/client-go/util/watchlist",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/internalversion",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/internalversion/validation",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/client-go/features",
        "//vendor/k8s.io/utils/ptr",
    ],
)
