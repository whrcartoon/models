package(
    default_visibility = ["//visibility:public"],
    features = ["-layering_check"],
)

cc_library(
    name = "mock_component",
    testonly = True,
    hdrs = ["mock_component.h"],
    deps = [
        "//dragnn/components/util:bulk_feature_extractor",
        "//dragnn/core:index_translator",
        "//dragnn/core/interfaces:component",
        "//dragnn/core/interfaces:transition_state",
        "//dragnn/core/util:label",
        "//dragnn/protos:data_proto_cc",
        "//dragnn/protos:spec_proto_cc",
        "//syntaxnet:base",
        "//syntaxnet:test_main",
    ],
)

cc_library(
    name = "mock_compute_session",
    testonly = True,
    hdrs = ["mock_compute_session.h"],
    deps = [
        "//dragnn/components/util:bulk_feature_extractor",
        "//dragnn/core:compute_session",
        "//dragnn/core:input_batch_cache",
        "//dragnn/core/util:label",
        "//dragnn/protos:data_proto_cc",
        "//dragnn/protos:spec_proto_cc",
        "//syntaxnet:base",
        "//syntaxnet:test_main",
    ],
)

cc_library(
    name = "mock_transition_state",
    testonly = True,
    hdrs = ["mock_transition_state.h"],
    deps = [
        "//dragnn/core/interfaces:transition_state",
        "//syntaxnet:base",
        "//syntaxnet:test_main",
    ],
)

cc_library(
    name = "fake_component_base",
    hdrs = ["fake_component_base.h"],
    deps = ["//dragnn/core/interfaces:component"],
)

cc_library(
    name = "generic",
    testonly = True,
    srcs = ["generic.cc"],
    hdrs = ["generic.h"],
    deps = [
        "//syntaxnet:base",
        "//syntaxnet:test_main",
    ],
)
