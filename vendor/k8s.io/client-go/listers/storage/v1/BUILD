load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "storage",
    srcs = [
        "csidriver.go",
        "csinode.go",
        "csistoragecapacity.go",
        "expansion_generated.go",
        "storageclass.go",
        "volumeattachment.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/listers/storage/v1",
    importpath = "k8s.io/client-go/listers/storage/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/storage/v1:storage",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/client-go/listers",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
