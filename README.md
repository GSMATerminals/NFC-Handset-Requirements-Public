# NFC Handset Requirements Public Repository #

This repository contains API documentation relating to the GSMA NFC Handset Requirements.

Each mobile OS has its API stored under a separate directory, which allows for future expansion of API definitions for platforms other than Android.

Under the root directory, you should see the appropriate file structure for aech mobile OS platform, as shown below, 
for the case of a Java-based platform such as Android:

```
NFC-Handset-Requirements-Public +
                                |
                                +- Android -+
                                |           |
                                |           +- com -+
                                |                    |
                                |                    +- gsma -+
                                |                             |
                                |                             +- services -+
                                |                                           |
                                |                                           +- nfc -+
                                |                                                   |
                                |                                                   +- SEController.java
                                |                                                   +- NfcController.java
                                |
                                +- OtherOS -+
                                +- AndOnotherOS -+
```

## Participation Rules ##

As a contributor to this effort, you are required to make a full contribution under the Apache 2 license (there is a copy in the file LICENSE in this directory). You are also required to add your copyright to any file you contribute or modify.

### Example of the file header for a NEW file contribution ###

Below is an example of the minimum information which musyt be present in every file header for a file committed to this repository. The sample code is suitable for C, C++ or Java source code. For any other language, the information and formatting should be as similar as possible to the version below.

In the sample below, the file is contributed in 2015 by the Yoyodyne Corporation.

```
/******************************************************************************
* API definition for supporting Foo functionality on an NFC-enabled
* Android handset
*
* Copyright (c) Yoyodyne Corporation 2015
*
*  Licensed under the Apache License, Version 2.0 (the "License");
*  you may not use this file except in compliance with the License.
*  You may obtain a copy of the License at
*
*      http://www.apache.org/licenses/LICENSE-2.0
*
*  Unless required by applicable law or agreed to in writing, software
*  distributed under the License is distributed on an "AS IS" BASIS,
*  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
*  See the License for the specific language governing permissions and
*  limitations under the License.
*******************************************************************************/

```

### Example of the file header for an update to an existing file ###

In this example, FoobarAcme Inc has made a change somewhere in the file, and as such will add its own copyright below the YoyoDyne Corportation copyright.

```
/******************************************************************************
* API definition for supporting Foo functionality on an NFC-enabled
* Android handset
*
* Copyright (c) Yoyodyne Corporation 2015
* Copyright (c) FoobarAcme Inc, 2015
*
*  Licensed under the Apache License, Version 2.0 (the "License");
*  you may not use this file except in compliance with the License.
*  You may obtain a copy of the License at
*
*      http://www.apache.org/licenses/LICENSE-2.0
*
*  Unless required by applicable law or agreed to in writing, software
*  distributed under the License is distributed on an "AS IS" BASIS,
*  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
*  See the License for the specific language governing permissions and
*  limitations under the License.
*******************************************************************************/

```


