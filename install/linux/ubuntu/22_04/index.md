---
layout: page
title: Install Swift
---

{% include install/_os_tabs.md linux="true" %}

{% include install/_linux_platforms_tabs.md ubuntu="true" %}

{% include install/_os_versions_tabs.md os_versions=site.data.install.ubuntu  name="Ubuntu" pressed="Ubuntu 22.04" %}

{% include install/_build_release.md platform="Ubuntu 22.04" docker_tag="jammy" aarch64="true"%}

{% include install/_build_snapshot.md platform="Ubuntu 22.04"
aarch64="true"
branch_dir="development" 
development="main" 
docker_tag="nightly-jammy" 
development_builds=site.data.builds.development.ubuntu2204 
aarch64_development_builds=site.data.builds.development.ubuntu2204-aarch64
development_2="release/6.0" 
docker_tag_2="nightly-6.0-jammy" 
development_builds_2=site.data.builds.swift-6_0-branch.ubuntu2204 aarch64_development_builds_2=site.data.builds.swift-6_0-branch.ubuntu2204-aarch64 
branch_dir_2="swift-6.0-branch"%}
