---
layout: custom
---
**OpenScanHub** is a service for static and dynamic analysis. By default it uses `Cppcheck`, `ShellCheck`, the static analyzers embedded in GCC and Clang, `find-unicode-control`, and the `Gitleaks` tool. Other tools for static and dynamic analysis can be enabled on demand while submitting an OpenScanHub scan.

OpenScanHub can analyze RPM packages and source code tarballs.

## Key Features

- It can perform differential scans i.e. compare newer version of a package with older version and report defects that were introduced in the newer version.
- It is extensible through [csmock](https://github.com/csutils/csmock) plugins and can scan any type of source code.
- It can collect reports from various analyzers in a single place.

## Who should use it?

It can be used by any developer. It can help to improve security and stability of projects by finding defects in the source code.

## Who uses it?

It is used inside Red Hat to scan releases of RHEL and a few other projects.

## How to use it?

We are currently in the process of building a public deployment of this service. Meanwhile, you can use it on your local system by following the developer documentation.

## Developers

Developer documentation can be found on [GitHub](https://github.com/openscanhub/openscanhub/blob/main/docs/development.md).

## Related Links

Code Scanning Utilities - [csutils](https://github.com/csutils)

## Contacts

Questions can be discussed on the [mailing list](https://lists.fedoraproject.org/archives/list/openscanhub@lists.fedoraproject.org/).
