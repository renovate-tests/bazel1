# this commit should be updated to a new commit
go_repository(
    name = "org_golang_x_crypto",
    commit = "ccddf3741a0cfcee0a62d34c18c2c5417a3761af",
    importpath = "golang.org/x/crypto",
)

# this commit should be updated to a versioned tag
go_repository(
    name = "com_github_pkg_errors",
    commit = "05ac58a23b8798a296fa64f7d9c1559904db4b98",  # v0.8.1
    importpath = "github.com/pkg/errors",
)

# this tag version should be updated
go_repository(
    name = "com_github_prometheus_prometheus",
    tag = "v2.6.1",
    importpath = "github.com/prometheus/prometheus",
)

# should find a new semantic git tag
git_repository(
    name = "build_bazel_rules_nodejs",
    remote = "https://github.com/bazelbuild/rules_nodejs.git",
    tag = "0.1.0",
)

# this http archive should be updated to a new release
http_archive(
    name = "io_bazel_rules_docker",
    url = "https://github.com/bazelbuild/rules_docker/archive/v0.5.1.tar.gz",
    strip_prefix = "rules_docker-0.5.1",
    sha256 = "29d109605e0d6f9c892584f07275b8c9260803bf0c6fcb7de2623b2bedc910bd",
)

http_archive(
    name="distroless",
    sha256="f7a6ecfb8174a1dd4713ea3b21621072996ada7e8f1a69e6ae7581be137c6dd6",
    strip_prefix="distroless-446923c3756ceeaa75888f52fcbdd48bb314fbf8",
    urls=["https://github.com/GoogleContainerTools/distroless/archive/446923c3756ceeaa75888f52fcbdd48bb314fbf8.tar.gz"]
)
