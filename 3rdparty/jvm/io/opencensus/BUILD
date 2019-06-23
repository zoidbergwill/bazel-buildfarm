java_library(
    name = "opencensus_api",
    exports = [
        "//external:jar/io/opencensus/opencensus_api"
    ],
    runtime_deps = [
        "//3rdparty/jvm/io/grpc:grpc_context"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_contrib_grpc_metrics",
    exports = [
        "//external:jar/io/opencensus/opencensus_contrib_grpc_metrics"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        ":opencensus_api"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_contrib_zpages",
    exports = [
        "//external:jar/io/opencensus/opencensus_contrib_zpages"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        ":opencensus_api",
        ":opencensus_contrib_grpc_metrics"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_exporter_metrics_util",
    exports = [
        "//external:jar/io/opencensus/opencensus_exporter_metrics_util"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        ":opencensus_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "opencensus_exporter_stats_prometheus",
    exports = [
        "//external:jar/io/opencensus/opencensus_exporter_stats_prometheus"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        "//3rdparty/jvm/io/prometheus:simpleclient",
        ":opencensus_api",
        ":opencensus_exporter_metrics_util"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_exporter_trace_jaeger",
    exports = [
        "//external:jar/io/opencensus/opencensus_exporter_trace_jaeger"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        "//3rdparty/jvm/io/jaegertracing:jaeger_client",
        ":opencensus_api",
        ":opencensus_exporter_trace_util"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_exporter_trace_util",
    exports = [
        "//external:jar/io/opencensus/opencensus_exporter_trace_util"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        ":opencensus_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)



java_library(
    name = "opencensus_impl",
    exports = [
        "//external:jar/io/opencensus/opencensus_impl"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/lmax:disruptor",
        ":opencensus_api",
        ":opencensus_impl_core"
    ],
    visibility = [
        "//visibility:public"
    ]
)



java_library(
    name = "opencensus_impl_core",
    exports = [
        "//external:jar/io/opencensus/opencensus_impl_core"
    ],
    runtime_deps = [
        "//3rdparty/jvm/com/google/guava:guava",
        ":opencensus_api"
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__"
    ]
)


