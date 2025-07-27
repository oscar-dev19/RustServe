


          
# RustServe: High-Performance Multithreaded HTTP Server

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A lightweight, blazing-fast HTTP server built from scratch in Rust with zero web framework dependencies. RustServe demonstrates Rust's powerful concurrency model and memory safety guarantees while delivering exceptional performance.

## Key Features

- **Pure Rust Implementation**: Built using only Rust's standard library and minimal dependencies
- **Custom Thread Pool**: Efficiently manages concurrent connections with a hand-crafted thread pool
- **Zero-Copy Architecture**: Optimized for minimal memory overhead and maximum throughput
- **Structured Logging**: Comprehensive logging with configurable verbosity levels
- **Graceful Shutdown**: Clean termination with proper resource cleanup
- **Static File Serving**: Efficiently serves HTML and other static content

## Technical Highlights

- Implements a custom thread pool for connection handling
- Uses Rust's ownership model to guarantee thread safety without locks
- Leverages non-blocking I/O for optimal performance
- Demonstrates advanced Rust patterns including channels, Arc, and Mutex
- Showcases proper error handling and resource management

## Performance

RustServe is designed for high throughput and low latency, making it suitable for production environments where performance is critical. The multithreaded architecture efficiently utilizes all available CPU cores.

## Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/rust_server.git
cd rust_server

# Build and run
cargo run

# Server will be available at http://127.0.0.1:7878
```

## Future Roadmap

- HTTP/2 support
- TLS/HTTPS implementation
- Dynamic content generation
- WebSocket support
- Request rate limiting and connection pooling

---

Built with ❤️ in Rust. Contributions welcome!
        
