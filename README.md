# New Project Template

This repository contains a template you can use to seed a repository for a
new open source project.

This template uses the Apache license (Expedia Group's default).

## How to use this template

1. Check it out from GitHub.
    * There is no reason to fork it.
2. Create a new local repository and copy the files from this repo into it.
3. Modify the `README.md`, `CONTRIBUTING.md`, and any files under `.github/` to represent your project, not the
   template project. Replace the `PUT_YOUR_TEAM_CONTACT_DETAILS_HERE` in 
   `CODE-OF-CONDUCT.md` with your team details (public email address or link 
   to GitHub team details).
4. Develop your new project!

``` shell
git clone https://github.com/ExpediaGroup/new-project
mkdir my-new-thing
cd my-new-thing
git init
cp ../new-project/* .
cp ../new-project/.gitignore .
git add *
git commit -a -m 'Boilerplate for new Expedia Group open source project'
```

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers (this is to help well-intentioned people avoid accidental copying that
doesn't comply with the license).

### Apache header:

    Copyright 2020 Expedia, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

# Legal
This project is based on [Google's New Project template](https://github.com/google/new-project).

This project is available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

Copyright 2021 Expedia, Inc.
