<!--
{% comment %}
Copyright 2018-2021 Elyra Authors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->

# CLAIMED - The Component Library for AI, Machine Learning, ETL, and Data Science

This repository contains the CLAIMED library [https://arxiv.org/abs/2103.03281](https://arxiv.org/abs/2103.03281).

IMPORTANT: This library is currently targeted for research purposes only and usage for production is discouraged at this point.
This library contains usable exemplars of components implemented as Jupyter notebooks. Those are tailored for the ElyraAI pipeline editor but of course can be used in other contexts as well.

Each notebook follows a similar format.

1. The first cell contains a description of the component itself.
2. The second cell installs all dependencies using pip3.
3. The third cell imports all dependencies.
4. The fourth cell contains a list of dependencies, input parameters, and return values as Python comments
5. The fifth cell reads the input parameters from environment variables.

Coming soon: A video and sample pipeline where you can see the component library in action. For now, please refer to the publication mentioned above for more information. This publication also contains a link to a sample repository with a working pipeline.
