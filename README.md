你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Kubernetes Helm

[![CircleCI](https://circleci.com/gh/kubernetes/helm.svg?style=svg)](https://circleci.com/gh/kubernetes/helm)
[![Go Report Card](https://goreportcard.com/badge/github.com/kubernetes/helm)](https://goreportcard.com/report/github.com/kubernetes/helm)

Helm is a tool for managing Kubernetes charts. Charts are packages of
pre-configured Kubernetes resources.

Use Helm to...

- Find and use [popular software packaged as Kubernetes charts](https://github.com/kubernetes/charts)
- Share your own applications as Kubernetes charts
- Create reproducible builds of your Kubernetes applications
- Intelligently manage your Kubernetes manifest files
- Manage releases of Helm packages

## Helm in a Handbasket

Helm is a tool that streamlines installing and managing Kubernetes applications.
Think of it like apt/yum/homebrew for Kubernetes.

- Helm has two parts: a client (`helm`) and a server (`tiller`)
- Tiller runs inside of your Kubernetes cluster, and manages releases (installations)
  of your charts.
- Helm runs on your laptop, CI/CD, or wherever you want it to run.
- Charts are Helm packages that contain at least two things:
  - A description of the package (`Chart.yaml`)
  - One or more templates, which contain Kubernetes manifest files
- Charts can be stored on disk, or fetched from remote chart repositories
  (like Debian or RedHat packages)

## Install

Binary downloads of the Helm client can be found at the following links:

- [OSX](https://kubernetes-helm.storage.googleapis.com/helm-v2.4.1-darwin-amd64.tar.gz)
- [Linux](https://kubernetes-helm.storage.googleapis.com/helm-v2.4.1-linux-amd64.tar.gz)
- [Linux 32-bit](https://kubernetes-helm.storage.googleapis.com/helm-v2.4.1-linux-386.tar.gz)

Unpack the `helm` binary and add it to your PATH and you are good to go!
macOS/[homebrew](https://brew.sh/) users can also use `brew install kubernetes-helm`.

To rapidly get Helm up and running, start with the [Quick Start Guide](docs/quickstart.md).

See the [installation guide](docs/install.md) for more options,
including installing pre-releases.

## Docs

Get started with the [Quick Start guide](docs/quickstart.md) or plunge into the [complete documentation](docs/index.md)

## Roadmap

The [Helm roadmap is currently located on the wiki](https://github.com/kubernetes/helm/wiki/Roadmap).

## Community, discussion, contribution, and support

You can reach the Helm community and developers via the following channels:

- [Kubernetes Slack](https://slack.k8s.io):
  - #helm-users
  - #helm-dev
- Mailing List: https://groups.google.com/forum/#!forum/kubernetes-sig-apps
- Developer Call: Thursdays at 9:30-10:00 Pacific. [https://zoom.us/j/4526666954](https://zoom.us/j/4526666954)

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).
