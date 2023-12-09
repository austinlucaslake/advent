# advent-2023

Advent of Code 2023.

---

[![Latest Release][release-badge]][release-url]
[![License][license-badge]](LICENSE)
[![CI Status][ci-badge]][ci-url]

---

## Build

To clone the repository on your local machine, please run the following git command in the terminal:
`git clone https://github.com/austinlucaslake/advent/tree/2023.git`

Assuming [Conan][conan-url] is installed, you may build the project as follows:
`conan build . -b=missing -pr=profile`

The naming-convention for each day's exectubate is as follows:
`./build/Release/day{NUMBER}`
With NUMBER being the number to that day (1-25)

Similarly, to build and run the program in debug mode, the following command may be used instead: 
`conan build . -b=missing -pr=profile -s=build_type=Debug && ./build/debug/day{NUMBER}`

[release-badge]: https://img.shields.io/github/v/release/austinlucaslake/advent/tree/2023
[release-url]: https://github.com/austinlucaslake/advent/tree/2023/releases/latest
[license-badge]: https://img.shields.io/github/license/austinlucaslake/advent/tree/2023
[ci-badge]: https://github.com/austinlucaslake/advent/tree/2023/actions/workflows/ci.yaml/badge.svg
[ci-url]: https://github.com/austinlucaslake/advent/tree/2023/actions
[conan-url]: https://conan.io/downloads
