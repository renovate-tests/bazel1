# this commit should be updated to a new commit
go_repository(
    name = "org_golang_x_crypto",
    commit = "ccddf3741a0cfcee0a62d34c18c2c5417a3761af",
    importpath = "golang.org/x/crypto",
)

# this commit should be updated to a versioned tag
go_repository(
    name = "com_github_pkg_errors",
    commit = "ffb6e22f01932bf7ac35e0bad9be11f01d1c8685",
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
    sha256="bca31ebedacbe38a12fbaf2270938533d0e97e9438a17229a73e4a601d06d23a",
    strip_prefix="distroless-033387ac8853e6cc1cd47df6c346bc53cbc490d8",
    urls=["https://github.com/GoogleContainerTools/distroless/archive/033387ac8853e6cc1cd47df6c346bc53cbc490d8.tar.gz"]
)
