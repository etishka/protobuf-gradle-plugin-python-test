# protobuf-gradle-plugin-python-test
This is an example project to demonstrate protobuf-gradle-plugin and Python conjunction

after building it with 'gradle build', the build directory contains both Java and Python source files.

The Python directory however doesn't contain a package indicator - `__init__.py` file, so it is not ready to be packaged and published into PyPi


https://github.com/google/protobuf-gradle-plugin/issues/241
