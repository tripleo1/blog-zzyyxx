# Blog OS

This repository contains the source code for the _Writing an OS in Rust_ series at [tripleo1.github.io/blog](https://tripleo1.github.io/blog).

If you have questions, open an issue or chat with us [on Gitter](https://gitter.im/phil-opp/blog_os).

## Where is the code?

The code for each post lives in a separate git branch. This makes it possible to see the intermediate state after each post.

**The code for the latest post is available [here][latest-post].**

[latest-post]: https://tripleo1.github.io/blog/tree/post-12

You can find the branch for each post by following the `(source code)` link in the [post list](#posts) below. The branches are named `post-XX` where `XX` is the post number, for example `post-03` for the _VGA Text Mode_ post or `post-07` for the _Hardware Interrupts_ post. For build instructions, see the Readme of the respective branch.

You can check out a branch in a subdirectory using [git worktree]:

[git worktree]: https://git-scm.com/docs/git-worktree

```
git worktree add code post-10
```

The above command creates a subdirectory named `code` that contains the code for the 10th post ("Heap Allocation").

## Posts

The goal of this project is to provide step-by-step tutorials in individual blog posts. We currently have the following set of posts:

**Bare Bones:**

- [A Freestanding Rust Binary](https://tripleo1.github.io/blog/freestanding-rust-binary/)
    ([source code](https://tripleo1.github.io/blog/tree/post-01))
- [A Minimal Rust Kernel](https://tripleo1.github.io/blog/minimal-rust-kernel/)
    ([source code](https://tripleo1.github.io/blog/tree/post-02))
- [VGA Text Mode](https://tripleo1.github.io/blog/vga-text-mode/)
    ([source code](https://tripleo1.github.io/blog/tree/post-03))
- [Testing](https://tripleo1.github.io/blog/testing/)
    ([source code](https://tripleo1.github.io/blog/tree/post-04))

**Interrupts:**

- [CPU Exceptions](https://tripleo1.github.io/blog/cpu-exceptions/)
    ([source code](https://tripleo1.github.io/blog/tree/post-05))
- [Double Faults](https://tripleo1.github.io/blog/double-fault-exceptions/)
    ([source code](https://tripleo1.github.io/blog/tree/post-06))
- [Hardware Interrupts](https://tripleo1.github.io/blog/hardware-interrupts/)
    ([source code](https://tripleo1.github.io/blog/tree/post-07))

**Memory Management:**

- [Introduction to Paging](https://tripleo1.github.io/blog/paging-introduction/)
    ([source code](https://tripleo1.github.io/blog/tree/post-08))
- [Paging Implementation](https://tripleo1.github.io/blog/paging-implementation/)
    ([source code](https://tripleo1.github.io/blog/tree/post-09))
- [Heap Allocation](https://tripleo1.github.io/blog/heap-allocation/)
    ([source code](https://tripleo1.github.io/blog/tree/post-10))
- [Allocator Designs](https://tripleo1.github.io/blog/allocator-designs/)
    ([source code](https://tripleo1.github.io/blog/tree/post-11))

**Multitasking**:

- [Async/Await](https://tripleo1.github.io/blog/async-await/)
    ([source code](https://tripleo1.github.io/blog/tree/post-12))

## First Edition Posts

The current version of the blog is already the second edition. The first edition is outdated and no longer maintained, but might still be useful. The posts of the first edition are:

<details><summary><i>Click to expand</i></summary>

**Bare Bones:**

- [A Minimal x86 Kernel](https://tripleo1.github.io/blog/multiboot-kernel.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_1))
- [Entering Long Mode](https://tripleo1.github.io/blog/entering-longmode.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_2))
- [Set Up Rust](https://tripleo1.github.io/blog/set-up-rust.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_3))
- [Printing to Screen](https://tripleo1.github.io/blog/printing-to-screen.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_4))

**Memory Management:**

- [Allocating Frames](https://tripleo1.github.io/blog/allocating-frames.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_5))
- [Page Tables](https://tripleo1.github.io/blog/modifying-page-tables.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_6))
- [Remap the Kernel](https://tripleo1.github.io/blog/remap-the-kernel.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_7))
- [Kernel Heap](https://tripleo1.github.io/blog/kernel-heap.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_8))

**Exceptions:**

- [Handling Exceptions](https://tripleo1.github.io/blog/handling-exceptions.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_9))
- [Double Faults](https://tripleo1.github.io/blog/double-faults.html)
      ([source code](https://tripleo1.github.io/blog/tree/first_edition_post_10))

**Additional Resources:**

- [Cross Compile Binutils](https://tripleo1.github.io/blog/cross-compile-binutils.html)
- [Cross Compile libcore](https://tripleo1.github.io/blog/cross-compile-libcore.html)
- [Set Up GDB](https://tripleo1.github.io/blog/set-up-gdb)
- [Handling Exceptions using Naked Functions](https://tripleo1.github.io/blog/handling-exceptions-with-naked-fns.html)
    - [Catching Exceptions](https://tripleo1.github.io/blog/catching-exceptions.html)
          ([source code](https://tripleo1.github.io/blog/tree/catching_exceptions))
    - [Better Exception Messages](https://tripleo1.github.io/blog/better-exception-messages.html)
          ([source code](https://tripleo1.github.io/blog/tree/better_exception_messages))
    - [Returning from Exceptions](https://tripleo1.github.io/blog/returning-from-exceptions.html)
          ([source code](https://tripleo1.github.io/blog/tree/returning_from_exceptions))

</details>

## License

This project, with exception of the `blog/content` folder, is licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  https://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or https://opensource.org/licenses/MIT)

at your option.

For licensing of the `blog/content` folder, see the [`blog/content/README.md`](blog/content/README.md).

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
