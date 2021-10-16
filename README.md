# basic-test-bazel

This exercise is about Bazel Build and C/C++ language.

**Exercise:** fix file *BUILD.bazel* in order to allow it to compile *test.cpp* into binary *app_test*.

To practice, use the following invitation link:  https://classroom.github.com/a/4cxjjKP7

More information: https://medium.com/@igormcoelho/configuring-bazel-build-with-gnu-c-c-on-windows-e27b2c66bed6

## Configuration on github actions / classroom

Build (must have a `package.json`):

```
npm install @bazel/bazelisk
```

Run (must setup `XDG_CACHE_HOME`):

```
export XDG_CACHE_HOME=. && ./node_modules/.bin/bazel build ... && ./node_modules/.bin/bazel run //:app_test
```
