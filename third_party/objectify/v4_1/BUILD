package_group(
    name = "specific_version",
    packages = ["//third_party/objectify"],
)

package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # MIT/X11

java_import(
    name = "v4_1",
    jars = ["objectify-4.1.3.jar"],
    srcjar = "objectify-4.1.3-src.jar",
    deps = [
        "@com_google_appengine_api_1_0_sdk",
        "@javax_servlet_api",
    ],
)
