<!--
# license: Licensed to the Apache Software Foundation (ASF) under one
#         or more contributor license agreements.  See the NOTICE file
#         distributed with this work for additional information
#         regarding copyright ownership.  The ASF licenses this file
#         to you under the Apache License, Version 2.0 (the
#         "License"); you may not use this file except in compliance
#         with the License.  You may obtain a copy of the License at
#
#           http://www.apache.org/licenses/LICENSE-2.0
#
#         Unless required by applicable law or agreed to in writing,
#         software distributed under the License is distributed on an
#         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#         KIND, either express or implied.  See the License for the
#         specific language governing permissions and limitations
#         under the License.
-->

# aemm-plugin-inappbrowser

This plugin provides an AEM in app web browser view that displays when calling `window.open()`. The in app browser view has header and footer bar. On the header bar, there is a Done button on left side to close the in app browser view. On the footer bar, there are previous, next, refresh and external buttons. The previous button takes to the previous viewed web site, the next button takes to the next viewed web site, the refresh button refreshes the current viewing web site and the external button takes to the external web browser view.

## Installation

cordova plugin add aemm-plugin-inappbrowser

### Supported Platforms

- iOS 8.0 and beyond

### Example

window.open("http://www.adobe.com");
