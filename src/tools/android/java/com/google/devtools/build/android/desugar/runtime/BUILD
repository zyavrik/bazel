# Description:
#   This is the extension package to support desugaring try-with-resources statements.

java_library(
    name = "throwable_extension",
    srcs = ["ThrowableExtension.java"],
    # This library must be compiled with java7, as we directly copy it to the desugared jar.
    javacopts = [
        "-source 7",
        "-target 7",
    ],
    visibility = ["//src/tools/android/java/com/google/devtools/build/android/desugar:__pkg__"],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
    visibility = ["//src/tools/android/java/com/google/devtools/build/android/desugar:__pkg__"],
)
