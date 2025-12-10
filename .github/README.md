## Overview

This is a hacky way of consolidating automated container builds for various applications into one single repository.

New container builds for any given app are triggered by changes to the corresponding Dockerfile, and will come out looking like this:

`ghcr.io/yoshieralf/containers:<app-name>`

See the [build workflow](https://github.com/yoshieralf/containers/blob/master/.github/workflows/build.yml) and [scripts](https://github.com/yoshieralf/containers/tree/master/.github/scripts) for implementation details.
