cc_binary(
    name = "ground_station",
    srcs = ["ground_station.cc"],
    deps = [
        "//protos:command_cc_grpc",
        "//protos:telemetry_cc_grpc",
        "@abseil-cpp//absl/flags:flag",
        "@abseil-cpp//absl/flags:parse",
        "@abseil-cpp//absl/strings:str_format",
        "@com_github_grpc_grpc//:grpc++",
        "@com_github_grpc_grpc//:grpc++_reflection",
    ],
)
