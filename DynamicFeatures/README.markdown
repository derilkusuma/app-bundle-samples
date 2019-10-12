

@@ -1,25 +1,25 @@
# Copyright 2019 Google LLC	# Copyright 2019 Google LLC
#	#
# Licensed under the Apache License, Version 2.0 (the "License");	# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.	# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at	# You may obtain a copy of the License at
#	#
#     https://www.apache.org/licenses/LICENSE-2.0	#     https://www.apache.org/licenses/LICENSE-2.0
#	#
# Unless required by applicable law or agreed to in writing, software	# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,	# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.	# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and	# See the License for the specific language governing permissions and
# limitations under the License.	# limitations under the License.
#	#
# GOOGLE SAMPLE PACKAGING DATA	# GOOGLE SAMPLE PACKAGING DATA
#	#
# This file is used by Google as part of our samples packaging process.	# This file is used by Google as part of our samples packaging process.
# End users may safely ignore this file. It has no relevance to other systems.	# End users may safely ignore this file. It has no relevance to other systems.
---	---
status:       PUBLISHED	status:       PUBLISHED
technologies: [Android]	technologies: [Android]
categories:   [Dynamic Apps]	categories:   [App Bundle]
languages:    [Kotlin, Java, Native]	languages:    [Kotlin, Java, Native]
solutions:    [Mobile]	solutions:    [Mobile]


 github:       android/app-bundle	github:       android/app-bundle
level:        INTERMEDIATE	level:        INTERMEDIATE
apiRefs:	apiRefs:
    - google:com.google.android.play.core.splitinstall.SplitInstallManager	    - google:com.google.android.play.core.splitinstall.SplitInstallManager
    - google:com.google.android.play.core.splitinstall.SplitInstallManagerFactory	    - google:com.google.android.play.core.splitinstall.SplitInstallManagerFactory
    - google:com.google.android.play.core.splitinstall.SplitInstallRequest	    - google:com.google.android.play.core.splitinstall.SplitInstallRequest
    - google:com.google.android.play.core.splitinstall.SplitInstallSessionState	    - google:com.google.android.play.core.splitinstall.SplitInstallSessionState
    - google:com.google.android.play.core.splitinstall.SplitInstallStateUpdatedListener	    - google:com.google.android.play.core.splitinstall.SplitInstallStateUpdatedListener
    - google:com.google.android.play.core.splitinstall.model.SplitInstallSessionStatus	    - google:com.google.android.play.core.splitinstall.model.SplitInstallSessionStatus
license: apache2
