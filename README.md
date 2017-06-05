<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Cordova for Ubuntu Touch

## What is it?

The repo contains patched version of Cordova for Ubuntu with the following improvements:

* WebView is automatically resized when on-screen keyboard is shown/hidden
* Copy/Paste is supported with touchscreen

## Requirements

- Original Ubuntu 16.04 image

## How to use

```
cordova platform update ubuntu https://github.com/milikhin/cordova-ubuntu.git --usegit
```
