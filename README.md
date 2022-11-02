This repository holds relases of Google's [copybara](https://github.com/google/copybara).

The jars in this repository (see releases)
have been produced by executing `bazel build //java/com/google/copybara:copybara_deploy.jar`
(as advertised in [copybara documentation](https://github.com/google/copybara#getting-started-using-copybara)).
Building `copybara` is not trivial, because it requires [bazel](https://github.com/bazelbuild/bazel) installed.
The purpose of this repo is to help with that.
