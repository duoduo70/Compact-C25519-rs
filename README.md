# Compact-X25519-rs
This library is a compact, zero-dependencies, single-file and almost no-std implementation of X25519.  
这个库是一个 X25519 的紧凑的、零依赖的、单文件的、几乎 no-std 的实现。

Transcibe from https://github.com/DavyLandman/compact25519.  
转写自 https://github.com/DavyLandman/compact25519 。

There are quite some advantages over older RSA based algorithms:  
与旧的基于 RSA 的算法相比，有很多优点：

- compact key size (32 bytes)
- Less opportunities to introduce side-channels
- Faster than other popular alternatives at the same 128bit security level

- 紧凑密钥大小（32 字节）
- 不容易遭到旁路攻击
- 在相同的 128 位安全级别下，比其他流行的替代方案更快

It does not require Cargo, nevertheless it is released as a Cargo package.  
它可以不依赖 Cargo ，但我仍提供了 Cargo 包形式的项目。

I don't want to publish it to crate.io now.  
我目前不想将其发布到 Crate.io 。

# Origins / 起源
Daniel Beer made the Python implementation, Davy Landman made the C transcibe. They released it under the public domain. To remain in the same spirit, this library is also licensed as Public Domain using the CC0 license.  
Daniel Beer 编写了基于 Python 的实现，Davy Landman 编写了 C 转写。它们都将自己的代码发布在了公有领域，基于他们的精神，这个存储库也使用 CC0 协议将其发布在公有领域上。

# TODO / 目标
I will transcribe it to the safe Rust.  
我将制作 Safe Rust 版的转写