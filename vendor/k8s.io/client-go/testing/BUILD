load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "testing",
    srcs = [
        "actions.go",
        "fake.go",
        "fixture.go",
        "interface.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/testing",
    importpath = "k8s.io/client-go/testing",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/gopkg.in/evanphx/json-patch.v4:json-patch_v4",
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/api/meta/testrestmapper",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/fields",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/json",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/apimachinery/pkg/util/strategicpatch",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/typed",
        "//vendor/sigs.k8s.io/yaml",
    ],
)
