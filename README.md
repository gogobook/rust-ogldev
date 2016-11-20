# OGLdev tutorials in Rust

[OGLdev](http://ogldev.atspace.co.uk/) is a very nice tutorial that introduces basic knowledge for writing a OpenGL program. The original tutorial is based on C. However, I want to reproduce the same results in [Rust](https://www.rust-lang.org/) for fun and learning. So that is why I created this repository.

I used [glium](https://github.com/tomaka/glium) to implement OpenGL in Rust. It is quite different from the one used by the original tutorials. You may see lots of difference between those tutorials and my implementations. Just stay calm. Take some time to read carefully. You will find that they are basically the same. At least they try to archive the same goals.

The [documents](http://tomaka.github.io/glium/glium/) of glium will be very useful when you try to understand what is going on in my implementations. Take a look :)

## The Goal of Each Tutorial

1. [To Create A Window](src/bin/tutorial_01.rs)
2. [To Draw A Dot](src/bin/tutorial_02.rs)

## How to Run It ?

Build them:

```
> cargo build
```

Run the `n`-th tutorial:

```
> target\debug\tutorial_n.exe
```
