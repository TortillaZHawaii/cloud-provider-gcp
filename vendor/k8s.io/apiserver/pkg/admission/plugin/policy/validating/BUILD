load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "validating",
    srcs = [
        "accessor.go",
        "caching_authorizer.go",
        "dispatcher.go",
        "errors.go",
        "initializer.go",
        "interface.go",
        "message.go",
        "plugin.go",
        "policy_decision.go",
        "typechecking.go",
        "validator.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/admission/plugin/policy/validating",
    importpath = "k8s.io/apiserver/pkg/admission/plugin/policy/validating",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cel-go/cel",
        "//vendor/github.com/google/cel-go/common/types",
        "//vendor/k8s.io/api/admissionregistration/v1:admissionregistration",
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/fields",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/json",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/sets",
        "//vendor/k8s.io/apimachinery/pkg/util/validation/field",
        "//vendor/k8s.io/apimachinery/pkg/util/version",
        "//vendor/k8s.io/apiserver/pkg/admission",
        "//vendor/k8s.io/apiserver/pkg/admission/initializer",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/cel",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/policy/generic",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/policy/matching",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/policy/validating/metrics",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/webhook/matchconditions",
        "//vendor/k8s.io/apiserver/pkg/apis/cel",
        "//vendor/k8s.io/apiserver/pkg/authentication/user",
        "//vendor/k8s.io/apiserver/pkg/authorization/authorizer",
        "//vendor/k8s.io/apiserver/pkg/cel",
        "//vendor/k8s.io/apiserver/pkg/cel/common",
        "//vendor/k8s.io/apiserver/pkg/cel/environment",
        "//vendor/k8s.io/apiserver/pkg/cel/library",
        "//vendor/k8s.io/apiserver/pkg/cel/openapi",
        "//vendor/k8s.io/apiserver/pkg/cel/openapi/resolver",
        "//vendor/k8s.io/apiserver/pkg/features",
        "//vendor/k8s.io/apiserver/pkg/util/feature",
        "//vendor/k8s.io/apiserver/pkg/warning",
        "//vendor/k8s.io/client-go/dynamic",
        "//vendor/k8s.io/client-go/informers",
        "//vendor/k8s.io/client-go/kubernetes",
        "//vendor/k8s.io/component-base/featuregate",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)
