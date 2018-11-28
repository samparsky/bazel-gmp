# LINUX
Required compilation tools.
```sh
$ apt-get install m4 libtool build-essential
```

# MAC OSX
Ensure XCode commandline tools is available

# BUILD
```sh
$ cd <dir>
$ bazel build @gnuimage//:gmplib
```

# DEBUG
```sh
$ cd <dir>
$ bazel build @gnuimage//:gmplib --sandbox_debug --verbose_failures
```

