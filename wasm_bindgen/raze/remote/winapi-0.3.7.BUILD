"""
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""

package(default_visibility = [
    # Public for visibility by "@raze__crate__version//" targets.
    #
    # Prefer access through "//wasm_bindgen/raze", which limits external
    # visibility to explicit Cargo.toml dependencies.
    "//visibility:public",
])

licenses([
    "notice",  # "MIT,Apache-2.0"
])

load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
    "rust_library",
    "rust_test",
)

# Unsupported target "build-script-build" with type "custom-build" omitted

rust_library(
    name = "winapi",
    srcs = glob(["**/*.rs"]),
    crate_features = [
        "consoleapi",
        "errhandlingapi",
        "fileapi",
        "handleapi",
        "knownfolders",
        "lmcons",
        "minschannel",
        "minwinbase",
        "minwindef",
        "ntdef",
        "ntsecapi",
        "objbase",
        "processenv",
        "profileapi",
        "schannel",
        "securitybaseapi",
        "shlobj",
        "sspi",
        "std",
        "sysinfoapi",
        "timezoneapi",
        "winbase",
        "wincon",
        "wincrypt",
        "winerror",
        "winnt",
        "winsock2",
        "ws2def",
        "ws2ipdef",
        "ws2tcpip",
    ],
    crate_root = "src/lib.rs",
    crate_type = "lib",
    edition = "2015",
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "0.3.7",
    deps = [
    ],
)
