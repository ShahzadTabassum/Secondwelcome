# Second Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`firstwelcome = "0.1.1"`

your cargo.toml file should look like this:
```
[package]
name = "hello_world"
version = "0.1.0"
authors = ["ShahzadTabassum <www.shahzadtabassum786@gmail.com>"]
edition = "2018"

[dependencies]
firstwelcome = "0.1.1"
```

In `src/main.rs` you can use like this:

```
use Secondwelcome;
fn main() {
    println!("Hello, world!");
    firstwelcome::hello();
}
```
following will also work:
```
use firstwelcome::hello;
fn main() {
    println!("Hello, world!");
    hello();
    }
```

now `cargo run` for results
