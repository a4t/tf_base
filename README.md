# tf_base

This is the base for developing Terraform modules.

git clone and rename and delete .git

## Usage

```
$ YOUR_REPOSITORY_NAME=[your repository name]
$ git clone https://github.com/a4t/tf_base.git ${YOUR_REPOSITORY_NAME}
$ cd ${YOUR_REPOSITORY_NAME}
$ rm -rf .git
```

## Test

```
$ make init
$ make test
```

## Version increment

```
$ make version+   # v0.0.1 -> v0.0.2
$ make version++  # v0.0.1 -> v0.1.0
$ make version+++ # v0.0.1 -> v1.0.0
```

## Release tag

```
$ make release-tag
```
