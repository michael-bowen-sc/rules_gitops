load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "amount.go",
        "generated.pb.go",
        "math.go",
        "quantity.go",
        "quantity_proto.go",
        "scale_int.go",
        "suffix.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "github.com/adobe/rules_gitops/vendor/k8s.io/apimachinery/pkg/api/resource",
    importpath = "k8s.io/apimachinery/pkg/api/resource",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/gopkg.in/inf.v0:go_default_library",
        "@com_github_gogo_protobuf//proto:go_default_library",
    ],
)
