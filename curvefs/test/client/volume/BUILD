#
#  Copyright (c) 2022 NetEase Inc.
#
#  Licensed under the Apache License, Version 2.0 (the "License");
#  you may not use this file except in compliance with the License.
#  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.
#

load("//:copts.bzl", "CURVE_TEST_COPTS")

cc_test(
    name = "curvefs_client_volume_test",
    srcs = glob([
        "*.cpp",
        "*.h",
    ]),
    copts = CURVE_TEST_COPTS,
    deps = [
        "//curvefs/src/client:fuse_client_lib",
        "//curvefs/test/volume/mock",
        "@com_google_absl//absl/strings",
        "@com_google_googletest//:gtest",
        "@com_google_googletest//:gtest_main",
        "//curvefs/test/client:mock",
    ],
)
