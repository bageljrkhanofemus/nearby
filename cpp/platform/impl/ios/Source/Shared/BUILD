# Copyright 2020 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
licenses(["notice"])

package(default_visibility = ["//platform/impl/ios:__subpackages__"])

objc_library(
    name = "Shared",
    srcs = [
        "GNCUtils.m",
    ],
    hdrs = [
        "GNCUtils.h",
    ],
    deps = [
        "//third_party/objective_c/google_toolbox_for_mac:GTM_StringEncoding",
        "//smhasher:libmurmur3",
    ],
)
