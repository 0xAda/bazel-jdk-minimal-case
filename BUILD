load("@rules_java//toolchains:default_java_toolchain.bzl", "VANILLA_TOOLCHAIN_CONFIGURATION", "default_java_toolchain")

default_java_toolchain(
    name = "my_toolchain",
    configuration = VANILLA_TOOLCHAIN_CONFIGURATION,
    java_runtime = "@openjdk//:openjdk",
)

java_library(
	name = "main",
	srcs = ["Main.java"],
)
