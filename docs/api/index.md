---
title: API extensions
parent: Template extension
layout: default
nav_order: 3
---

# API extensions

In this page, please document how your extension affects (if any) the optional HTTP parameters of the [API resolvers](https://skg-if.github.io/api/) described in the core specification of the SKG-IF.

Additionally, you are free to specify additional methods with customised behaviour that your extension requires to provide.

**Attention!** To prevent possible clashes with other extensions, each extension is assigned a unique prefix (e.g., the acronym you provided upon requesting an extension) that you need to prepend when defining api methods, or defining HTTP paramentes for core API resolvers.