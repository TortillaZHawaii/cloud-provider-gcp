load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "expr",
    srcs = [
        "checked.pb.go",
        "eval.pb.go",
        "explain.pb.go",
        "syntax.pb.go",
        "value.pb.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/cel.dev/expr",
    importpath = "cel.dev/expr",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/genproto/googleapis/rpc/status",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
        "//vendor/google.golang.org/protobuf/types/known/anypb",
        "//vendor/google.golang.org/protobuf/types/known/durationpb",
        "//vendor/google.golang.org/protobuf/types/known/emptypb",
        "//vendor/google.golang.org/protobuf/types/known/structpb",
        "//vendor/google.golang.org/protobuf/types/known/timestamppb",
    ],
)
