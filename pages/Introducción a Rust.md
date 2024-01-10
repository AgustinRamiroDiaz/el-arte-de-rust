# Por qué Rust?
![Program software in rust by Taewyth | Fiverr](https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/222485243/original/6c521669a87de73c1c57a8e5f625b5e6e2caf36f/program-software-in-rust.png)
- # Recursos Online
	- https://www.rust-lang.org/
	  ![image.png](../assets/image_1704925052406_0.png)
	- https://doc.rust-lang.org/book/
	  ![image.png](../assets/image_1704925208540_0.png)
	- https://rustlings.cool/
	  ![image.png](../assets/image_1704926579584_0.png)
- # Creando un proyecto con `cargo`
	- ```shell
	  # https://www.rust-lang.org/es/learn/get-started
	  $ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
	  $ cargo --version
	  cargo 1.75.0 (1d8b05cdd 2023-11-20)
	  ```
	- ```shell
	  $ cargo new aprendiendo-rust
	  ```
	- ```shell
	  $ tree
	  .
	  ├── Cargo.toml
	  └── src
	      └── main.rs
	  ```
	- ```rust
	  // src/main.rs
	  fn main() {
	      println!("Hello, world!");
	  }
	  ```
	- ```shell
	  $ cargo run
	     Compiling aprendiendo-rust v0.1.0 (/...)
	      Finished dev [unoptimized + debuginfo] target(s) in 0.43s
	       Running `target/debug/aprendiendo-rust`
	  Hello, world!
	  ```