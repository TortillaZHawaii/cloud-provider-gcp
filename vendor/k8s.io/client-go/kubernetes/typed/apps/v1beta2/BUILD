load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1beta2",
    srcs = [
        "apps_client.go",
        "controllerrevision.go",
        "daemonset.go",
        "deployment.go",
        "doc.go",
        "generated_expansion.go",
        "replicaset.go",
        "statefulset.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/apps/v1beta2",
    importpath = "k8s.io/client-go/kubernetes/typed/apps/v1beta2",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/apps/v1beta2",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/apps/v1beta2",
        "//vendor/k8s.io/client-go/gentype",
        "//vendor/k8s.io/client-go/kubernetes/scheme",
        "//vendor/k8s.io/client-go/rest",
    ],
)
