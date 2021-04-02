# RSSit

RSSit is a program written in [Rust](https://www.rust-lang.org/) that aggregates content from 
social news sites and publishes RSS feeds.

### Supported News Sites

  - Hacker News

### Supported Publishing Platforms

  - Google Cloud Storage

## Installation

Use the package manager [cargo](https://doc.rust-lang.org/cargo/) to install foobar.

```bash
cargo install rssit --git git@github.com:glenkim/rssit.git
```

## Usage

```bash
SERVICE_ACCOUNT=<service account json file path> CLOUD_STORAGE_BUCKET=<cloud storage bucket name> rssit
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)