# New Project Template

This repository contains a template that can be used to seed a repository for a new open source project.

This template uses the Apache license (Expedia Group's default).

## How to use this template

1. In GitHub UI, click "Use this template".
   - Set the owner is `ExpediaGroup`
   - Set visibility to `public`
   - Uncheck "Include all branches"
2. Clone locally and create a new branch
3. Code!
4. Update any applicable files from the template, including `README.md` and `CONTRIBUTING.md`.
5. Update `.github/dependabot.yml` to also include package updates for any languages used.
6. Use Actions
   - A pull request workflow is included but needs to be updated to correctly test and lint the project.
   - A release workflow is included that will create a tag and release on merges to main. See [Semantic Release](https://github.com/semantic-release/semantic-release) for more information.
7. Develop your new project!

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers (this is to help well-intentioned people avoid accidental copying that
doesn't comply with the license). Test files are considered source code.

### Apache header

    Copyright [yyyy] Expedia, Inc.  <-- Remember to replace with the current year here

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

## Legal

This project is based on [Google's New Project template](https://github.com/google/new-project).

This project is available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

Copyright 2021 Expedia, Inc.
