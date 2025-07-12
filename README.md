# Rust Crash Course

[contributors-shield]: https://img.shields.io/github/contributors/cyfrin/rust-crash-course.svg?style=for-the-badge
[contributors-url]: https://github.com/cyfrin/rust-crash-course/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cyfrin/rust-crash-course.svg?style=for-the-badge
[forks-url]: https://github.com/cyfrin/rust-crash-course/network/members
[stars-shield]: https://img.shields.io/github/stars/cyfrin/rust-crash-course.svg?style=for-the-badge
[stars-url]: https://github.com/cyfrin/rust-crash-course/stargazers
[issues-shield]: https://img.shields.io/github/issues/cyfrin/rust-crash-course.svg?style=for-the-badge
[issues-url]: https://github.com/cyfrin/rust-crash-course/issues
[license-shield]: https://img.shields.io/github/license/cyfrin/rust-crash-course.svg?style=for-the-badge
[license-url]: https://github.com/cyfrin/rust-crash-course/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

<div align="center">

[![Stargazers][stars-shield]][stars-url] [![Forks][forks-shield]][forks-url] [![Contributors][contributors-shield]][contributors-url] [![Issues][issues-shield]][issues-url] [![GPLv3 License][license-shield]][license-url]

<p align="center">
    <br />
    <a href="https://cyfrin.io/">
        <img src=".github/images/poweredbycyfrinbluehigher.png" width="145" alt=""/></a>
            <a href="https://updraft.cyfrin.io/courses/aave-v3">
        <img src=".github/images/coursebadge.png" width="242.3" alt=""/></a>
    <br />
</p>
</div>

This repository houses course resources and [discussions](https://github.com/Cyfrin/rust-crash-course/discussions) for the course.

Please refer to this for an in-depth explanation of the content:

- [Website](https://updraft.cyfrin.io) - Join Cyfrin Updraft and enjoy 50+ hours of smart contract development courses
- [Twitter](https://twitter.com/CyfrinUpdraft) - Stay updated with the latest course releases
- [LinkedIn](https://www.linkedin.com/school/cyfrin-updraft/) - Add Updraft to your learning experiences
- [Discord](https://discord.gg/cyfrin) - Join a community of 3000+ developers and auditors
- [Codehawks](https://codehawks.com) - Smart contracts auditing competitions to help secure web3

# Course intro

- [Course intro](./notes/course_intro.md)
- [Setup](./notes/course_setup.md)

# Rust intro

- [Install cargo](./notes/install.md)
- [Hello world](./topics/hello/README.md)
- [Variable](./topics/variable/README.md)
- [Function](./topics/function/README.md)

# Data types

- [Scalar types](./topics/scalar/README.md)
- [Tuple](./topics/tuple/README.md)
- [Array](./topics/array/README.md)
- [`String` and `&str`](./topics/string/README.md)
- [Enum](./topics/enum_type/README.md)
- [Struct](./topics/struct_type/README.md)
- [Vector](./topics/vector/README.md)
- [Hash map](./topics/hash_map/README.md)

# Control flow

- [If / else](./topics/if_else/README.md)
- [Loop](./topics/for_loop/README.md)
- [Match](./topics/pattern_match/README.md)
- [If let](./topics/if_let/README.md)

# Ownership

- [Stack and heap](./topics/stack_heap/README.md)
- [Ownership](./topics/ownership/README.md)
- [Borrowing rules](./topics/borrowing_rules/README.md)

# Error handling

- [Error handling](./topics/error/README.md)
- [`unwrap` and `expect`](./topics/unwrap/README.md)
- [`?`](./topics/question/README.md)

# Modules

- [Mod](./topics/modules/README.md)

# Generic types and traits

- [Generic types](./topics/generic_type/README.md)
- [Methods](./topics/method/README.md)
- [Trait](./topics/trait_basic/README.md)
- [Generic trait](./topics/generic_trait/README.md)
- [Trait bound](./topics/trait_bound/README.md)
- [Lifetime](./topics/lifetime/README.md)
- [Iterator](./topics/iterator_adaptors/README.md)
- [Iterator adaptors](./topics/iterator_adaptors/README.md)

# Concurrency

- [`async` / `await`](./topics/async_await/README.md)
- [Thread vs `async` / `await`](./topics/async_await/README.md)
- [`join!` and `select!` macros](./topics/join_select/README.md)

# Resources

- [Rust](https://www.rust-lang.org/)
- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [rustlings](https://github.com/rust-lang/rustlings/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust playground](https://play.rust-lang.org/)
- [Rust Cheatsheet](https://cheats.rs/)

# Notes

Execute all tests in `solutions` folder

```shell
find topics -type d -name solutions -exec bash -c 'cd "$0" && cargo test' {} \;
```
