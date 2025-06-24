# github-actions-learning

**Branch Status:**

| Branch | Status |
|--------|--------|
| ![Main](https://img.shields.io/badge/main-blue) | ![Hello World Python (main)](https://github.com/hawaii-in-paradise/github-actions-learning/actions/workflows/hello-world.yml/badge.svg?branch=main) |
| ![Load](https://img.shields.io/badge/load-orange) | ![Hello World Python (load)](https://github.com/hawaii-in-paradise/github-actions-learning/actions/workflows/hello-world.yml/badge.svg?branch=load) |
| ![Stage](https://img.shields.io/badge/stage-yellow) | ![Hello World Python (stage)](https://github.com/hawaii-in-paradise/github-actions-learning/actions/workflows/hello-world.yml/badge.svg?branch=stage) |
| ![Dev](https://img.shields.io/badge/dev-purple) | ![Hello World Python (dev)](https://github.com/hawaii-in-paradise/github-actions-learning/actions/workflows/hello-world.yml/badge.svg?branch=dev) |

The intended purpose of this is to learn github actions.  By the end of this tutorial I would have learned how to use a github action and have a badge on my README showing a passing pipeline.

To keep things simple the first lesson will create a running pipeline that shows a hello world prompt using a python script.

Then as things progress I will be able then re-use this pipeline as a sub-module into other branches that will be able to run using the agents within this pipeline.