# jitdocker

![](art/jitdocker.png)

A docker registry allows build on pull just in time.

Features:

* Support build script similar .travis.yml
* Support github commit/tag/branch
* Support auto-test
* Support stackfile
* Support webhook
* Support redirect registry
* Support private registry (pay)
* Support authentication: ssh-key, oauth
* Support workflow
* Support badges
* Support webhook back (listen other github repo on push)

## Usage

commit:

```sh
docker pull github.com/yongjhih/docker-parse-server:7a732ea
```

branch:

```sh
docker pull github.com/yongjhih/docker-parse-server:dev
```

tag:

```sh
docker pull github.com/yongjhih/docker-parse-server:2.1.3
```

folder:

```sh
docker pull github.com/yongjhih/docker-parse-server/dev # default master branch
```

