package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
)

rust_binary(
    name = "hello_out_dir",
    srcs = ["src/main.rs"],
    out_dir_tar = ":repacked_srcs.tar.gz"
)
