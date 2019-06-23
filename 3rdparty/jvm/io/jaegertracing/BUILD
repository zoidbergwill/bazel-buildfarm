java_library(
    name = "jaeger_client",
    exports = [
        "//external:jar/io/jaegertracing/jaeger_client"
    ],
    runtime_deps = [
        ":jaeger_core",
        ":jaeger_thrift",
        ":jaeger_tracerresolver"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jaeger_core",
    exports = [
        "//external:jar/io/jaegertracing/jaeger_core"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/code/gson:gson",
        "//3rdparty/jvm/io/opentracing:opentracing_api",
        "//3rdparty/jvm/io/opentracing:opentracing_util",
        "//3rdparty/jvm/org/slf4j:slf4j_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jaeger_thrift",
    exports = [
        "//external:jar/io/jaegertracing/jaeger_thrift"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/squareup/okhttp3:okhttp",
        "//3rdparty/jvm/org/apache/thrift:libthrift",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
        ":jaeger_core"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "jaeger_tracerresolver",
    exports = [
        "//external:jar/io/jaegertracing/jaeger_tracerresolver"
    ],
    runtime_deps = [
        "//3rdparty/jvm/io/opentracing/contrib:opentracing_tracerresolver",
        ":jaeger_core"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


