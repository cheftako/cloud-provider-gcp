load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["connectivity.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/clientv3/balancer/connectivity",
    importpath = "go.etcd.io/etcd/clientv3/balancer/connectivity",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/go.uber.org/zap:go_default_library",
        "//vendor/google.golang.org/grpc/connectivity:go_default_library",
    ],
)
