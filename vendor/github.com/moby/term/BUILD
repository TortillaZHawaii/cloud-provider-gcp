load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "term",
    srcs = [
        "ascii.go",
        "doc.go",
        "proxy.go",
        "term.go",
        "term_unix.go",
        "term_windows.go",
        "termios_bsd.go",
        "termios_nonbsd.go",
        "termios_unix.go",
        "termios_windows.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/moby/term",
    importpath = "github.com/moby/term",
    visibility = ["//visibility:public"],
    deps = select({
        "@io_bazel_rules_go//go/platform:aix": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:android": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:darwin": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:dragonfly": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:freebsd": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:illumos": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:ios": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:js": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:linux": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:netbsd": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:openbsd": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:plan9": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:solaris": [
            "//vendor/golang.org/x/sys/unix",
        ],
        "@io_bazel_rules_go//go/platform:windows": [
            "//vendor/github.com/moby/term/windows",
            "//vendor/golang.org/x/sys/windows",
        ],
        "//conditions:default": [],
    }),
)
