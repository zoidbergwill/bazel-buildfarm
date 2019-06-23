java_library(
    name = "opentracing_api",
    exports = [
        "//external:jar/io/opentracing/opentracing_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "opentracing_noop",
    exports = [
        "//external:jar/io/opentracing/opentracing_noop"
    ],
    runtime_deps = [
        ":opentracing_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "opentracing_util",
    exports = [
        "//external:jar/io/opentracing/opentracing_util"
    ],
    runtime_deps = [
        ":opentracing_api",
        ":opentracing_noop"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


