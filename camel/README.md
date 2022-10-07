Will/JH experiment to build a Docker container containing a shell script with Bazel

```
$ bazel run //wdjhdocker:wdjhtestdocker --action_env="ASDF_DATA_DIR=/Users/tech/.asdf" --action_env="ASDF_PYTHON_VERSION=3.10.2"
$ docker run -it bazel/wdjhdocker:wdjhtestdocker
```

`--action_env` parameters are only required if Python3 is installed via asdf.
