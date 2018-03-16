# Wrapper Cookbook as TODO List

This repo demonstrates how to use wrapper profiles and start with a green 
baseline.

1.  Clone the repo.
1.  `cd inspec-wrapper-as-todo/baseline`
1.  `kitchen verify`

A fully functional testing environment is available.

Add the ssh-baseline profile.

1.  Checkout branch named `01-add-ssh-baseline`
1.  `kitchen verify`

The cookbook is now using the ssh-baseline profile but there are a ton of 
failures.  That does not feel or look good.  Let's start with passing tests.

Add a wrapper profile and skip controls to get to red.

1.  Checkout branch named `02-wrapper-profile`
1.  `kitchen verify`

Everything is green!
# License

|                      |                                          |
|:---------------------|:-----------------------------------------|
| **Author:**          | Nathen Harvey (<nharvey@chef.io>)
| **Copyright:**       | Copyright 2018, Chef Software, Inc.
| **License:**         | Apache License, Version 2.0

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

