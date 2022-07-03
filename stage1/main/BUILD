load("@rules_cc//cc:defs.bzl", "cc_binary")

# 编译：bazel build //main:hello-world
# 编译后执行：bazel run //main:hello-world
# 查看依赖：bazel query --notool_deps --noimplicit_deps "deps(//main:hello-world)" --output graph
# xdot <(bazel query --notool_deps --noimplicit_deps "deps(//main:hello-world)" --output graph)
cc_binary(
    name = "hello-world",
    srcs = ["hello-world.cc"],
)