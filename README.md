# Linux Canaries

When building Linux kernel testing systems, it's necessary to validate that
failures are detected. The branches in this repository each fail (or pass) in a
very specific way, as noted in the branch names. Each of the branches and tags
in this repository are expected to not change, so that they can be used for
integration/regression testing.

## Reference Cases

- [v5.4_branch](https://github.com/Linaro/linux-canaries/tree/v5.4_branch):
  Reference branch that resolves to v5.4 release. That is, v5.4_branch and v5.4
  both resolve to commit 219d54332a09e8d8741c1e1982f5eae56099de85.

## Build Failures

- [arm64_build_broken](https://github.com/Linaro/linux-canaries/tree/arm64_build_broken):
  v5.3-rc4-1-g14626a244b97, build fails for arm64.

## Boot Failures

- [all_boot_broken](https://github.com/Linaro/linux-canaries/tree/all_boot_broken):
  v5.6-1-g3982030ccb01, boot fails for all architectures
