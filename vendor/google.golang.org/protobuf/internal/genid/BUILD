load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "genid",
    srcs = [
        "any_gen.go",
        "api_gen.go",
        "descriptor_gen.go",
        "doc.go",
        "duration_gen.go",
        "empty_gen.go",
        "field_mask_gen.go",
        "go_features_gen.go",
        "goname.go",
        "map_entry.go",
        "name.go",
        "source_context_gen.go",
        "struct_gen.go",
        "timestamp_gen.go",
        "type_gen.go",
        "wrappers.go",
        "wrappers_gen.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/protobuf/internal/genid",
    importpath = "google.golang.org/protobuf/internal/genid",
    visibility = ["//vendor/google.golang.org/protobuf:__subpackages__"],
    deps = ["//vendor/google.golang.org/protobuf/reflect/protoreflect"],
)
