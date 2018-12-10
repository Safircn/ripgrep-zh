## grep的正则表达式

该`grep-regex`crate提供了一个实现`Matcher`来自的特质`grep-matcher`箱.这个实现允许Rust的正则表达式引擎用于`grep`用于快速线路搜索的箱子.

[![Linux build status](https://api.travis-ci.org/BurntSushi/ripgrep.svg)](https://travis-ci.org/BurntSushi/ripgrep)
[![Windows build status](https://ci.appveyor.com/api/projects/status/github/BurntSushi/ripgrep?svg=true)](https://ci.appveyor.com/project/BurntSushi/ripgrep)
[![](https://img.shields.io/crates/v/grep-regex.svg)](https://crates.io/crates/grep-regex)

麻省理工学院或MIT下的双重许可[UNLICENSE](http://unlicense.org).

### 文档

<https://docs.rs/grep-regex>

**注意:**您可能不想直接使用此包.相反,你应该更喜欢在中定义的外观[`grep`](https://docs.rs/grep)箱.

### 用法

将此添加到您的`Cargo.toml`:

```toml
[dependencies]
grep-regex = "0.1"
```

这对你的箱子根:

```rust
extern crate grep_regex;
```