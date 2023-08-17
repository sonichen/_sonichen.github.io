# indicatif 

使用`indicatif` crate来实现显示进度条和处理过程的功能。

## 添加依赖

```toml
[dependencies]
indicatif = "0.17.0"
```

## 实例代码

```rust
use std::thread;
use std::time::Duration;

use indicatif::ProgressBar;

fn main() {
    let pb = ProgressBar::new(1024);
    for _ in 0..1024 {
        thread::sleep(Duration::from_millis(5));
        pb.inc(1);
    }
    pb.finish_with_message("done");
}
```

控制台输出

![image-20230804231723781](D:\Workplace\github\sonichen.github.io\docs\Rust\assets\image-20230804231723781-1691162254643-1.png)



## Reference

[1] https://github.com/console-rs/indicatif