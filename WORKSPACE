workspace(name = "envoy")

local_repository(
    name = "envoy",
    path = "envoy",
)

local_repository(
    name = "envoy_auth",
    path = "envoy_auth",
)

load("@envoy//bazel:repositories.bzl", "envoy_dependencies")
load("@envoy//bazel:cc_configure.bzl", "cc_configure")

envoy_dependencies()
cc_configure()
