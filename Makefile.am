## Platform conformance tests

## Copyright 2017 Mo McRoberts.
##
##  Licensed under the Apache License, Version 2.0 (the "License");
##  you may not use this file except in compliance with the License.
##  You may obtain a copy of the License at
##
##      http://www.apache.org/licenses/LICENSE-2.0
##
##  Unless required by applicable law or agreed to in writing, software
##  distributed under the License is distributed on an "AS IS" BASIS,
##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
##  See the License for the specific language governing permissions and
##  limitations under the License.

SUBDIRS = tests

EXTRA_DIST = LICENSE-2.0

reconf:
	( cd ${top_srcdir} && autoreconf -fvi ) && \
		${CONFIG_SHELL} ./config.status --recheck && \
		${CONFIG_SHELL} ./config.status
