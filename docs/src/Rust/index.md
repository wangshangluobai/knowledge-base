
# Rust

### 关于变量理解记录
从 `Javascript` 开发者的角度去理解 `Rust` 的变量规则

  `Rust` 对所有权的定义规则

    1. Rust 中每个值都有一个所有者。
    2. 值在任何时刻有且仅有一个所有者。
    3. 当所有者离开作用域时，这个值将被丢弃。

  `Rust` 中提到的 \`所有权\` 是指内存中存储的数据，可以被源码中哪个变量使用。