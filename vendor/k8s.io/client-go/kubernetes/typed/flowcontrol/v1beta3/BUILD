load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1beta3",
    srcs = [
        "doc.go",
        "flowcontrol_client.go",
        "flowschema.go",
        "generated_expansion.go",
        "prioritylevelconfiguration.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta3",
    importpath = "k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta3",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/flowcontrol/v1beta3",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/flowcontrol/v1beta3",
        "//vendor/k8s.io/client-go/gentype",
        "//vendor/k8s.io/client-go/kubernetes/scheme",
        "//vendor/k8s.io/client-go/rest",
    ],
)
