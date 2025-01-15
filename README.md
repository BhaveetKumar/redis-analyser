# Redis Data Analyzer

Redis Data Analyzer is a Rust-based tool for analyzing Redis data with high performance and reliability. It provides insights into key distribution, memory usage, data types, and key expiry details. With customizable filters and exportable reports, it helps optimize Redis usage for improved application performance and resource efficiency. Additionally, it helps convert PII (Personally Identifiable Information) to decrypted data, enabling secure and compliant analysis.

## Features
- **Key Distribution Analysis**: Understand the spread of keys across your Redis database.
- **Memory Usage Insights**: Analyze how memory is consumed by different keys or key types.
- **Key Expiry Details**: View expiring keys and their time-to-live (TTL).
- **Data Type Metrics**: Gain insights into usage patterns of various Redis data types (strings, hashes, sets, etc.).
- **Customizable Filters**: Filter results based on key patterns or namespaces.
- **Exportable Reports**: Generate analysis reports in JSON or other formats.
- **High Performance**: Built using Rust for efficient and scalable analysis.
- **PII Decryption Support**: Convert PII data to decrypted format for secure analysis.

## Installation
1. Ensure you have [Rust](https://www.rust-lang.org/) installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/redis-data-analyzer.git
   ```
3. Build the project:
   ```bash
   cd redis-data-analyzer
   cargo build --release
   ```

## Usage
Run the analyzer with your Redis connection details:
```bash
./target/release/redis-data-analyzer --host <REDIS_HOST> --port <REDIS_PORT> --auth <PASSWORD>
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
