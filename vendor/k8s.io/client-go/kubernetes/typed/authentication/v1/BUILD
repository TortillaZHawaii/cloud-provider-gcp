load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "authentication",
    srcs = [
        "authentication_client.go",
        "doc.go",
        "generated_expansion.go",
        "selfsubjectreview.go",
        "tokenreview.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/authentication/v1",
    importpath = "k8s.io/client-go/kubernetes/typed/authentication/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/authentication/v1:authentication",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/client-go/gentype",
        "//vendor/k8s.io/client-go/kubernetes/scheme",
        "//vendor/k8s.io/client-go/rest",
    ],
)
