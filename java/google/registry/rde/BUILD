package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

java_library(
    name = "rde",
    srcs = glob(["*.java"]),
    deps = [
        "//java/google/registry/config",
        "//java/google/registry/gcs",
        "//java/google/registry/keyring/api",
        "//java/google/registry/mapreduce",
        "//java/google/registry/mapreduce/inputs",
        "//java/google/registry/model",
        "//java/google/registry/request",
        "//java/google/registry/request/auth",
        "//java/google/registry/request/lock",
        "//java/google/registry/tldconfig/idn",
        "//java/google/registry/util",
        "//java/google/registry/xjc",
        "//java/google/registry/xml",
        "//third_party/jsch/v0_1_53",
        "//third_party/objectify:objectify-v4_1",
        "@com_google_appengine_api_1_0_sdk",
        "@com_google_appengine_tools_appengine_gcs_client",
        "@com_google_appengine_tools_appengine_mapreduce",
        "@com_google_auto_factory",
        "@com_google_auto_value",
        "@com_google_code_findbugs_jsr305",
        "@com_google_dagger",
        "@com_google_guava",
        "@com_google_re2j",
        "@javax_servlet_api",
        "@joda_time",
        "@org_bouncycastle_bcpg_jdk15on",
        "@org_bouncycastle_bcpkix_jdk15on",
    ],
)
