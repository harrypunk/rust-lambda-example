### AWS Lambda with Rust  
https://blog.knoldus.com/aws-lambda-with-rust/

```
rustup target add x86_64-unknown-linux-musl
```
```
cargo build --release --target x86_64-unknown-linux-musl
```
```
zip -j rust.zip ./target/x86_64-unknown-linux-musl/release/bootstrap
```
