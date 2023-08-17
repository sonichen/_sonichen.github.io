## **MDA File Design**

working



<HR>

## **sensleak 0.1.0 - scan git repo secrets**

sensleak is a Rust-based tool that scans Git repositories for sensitive data, specifically targeting sensitive information such as passwords, API keys, certificates, and private keys embedded within code.

**Technology**

- Development Language: Rust
- Command-line Interaction: [clap.rs](https://github.com/clap-rs/clap)
- Git Repository Operations: [git2](https://github.com/rust-lang/git2-rs)
- Web Framework: [axum](https://github.com/tokio-rs/axum)
- Auto-generated OpenAPI Documentation: [utoipa](https://github.com/juhaku/utoipa)

**Feature**

- **Enhanced Security.** Develop the tool in Rust to ensure improved security and memory safety.
- **Command-line Interface**. Create a user-friendly command-line tool that generates a comprehensive test report.
- **REST API with Access Control**. Enable the tool to run as a service and provide access control through a REST API. Utilize Swagger to generate API documentation.
- **Concurrent Scanning**. Utilize a thread pool to control concurrent scanning of secrets, thereby improving overall efficiency.
- **Batch Processing**. Implement batch processing of files to further optimize the scanning process and enhance efficiency.

**Github**

[https://github.com/open-rust-initiative/sensleak-rs](https://github.com/open-rust-initiative/sensleak-rs)