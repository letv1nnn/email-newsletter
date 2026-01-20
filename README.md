# Email Newsletter

> NOTE: The following code is my walkthrough of [***Zero to Production in Rust***](https://www.amazon.de/-/en/Zero-Production-Rust-introduction-development/dp/B0BHLDMFDQ/ref=sr_1_1?crid=CVF7QHGFJXNB&dib=eyJ2IjoiMSJ9.nM8mT2Cju-DULZ6qlNeY1aRzi4U2ErjMQ_oYewKPfT70fbm8eYdJiOWDDUizVq3LorjXzeEdFt2SD1BOoZskdTrd-IebUw83c2DsCM-_anVDqSSZwqA_Jgfm01SY8qxdUTqhZVW1dXJamjkzISaR1eN29XIpmkIUWTt9khQpMHb9wlbGcVhPSn5EZZHEHODrdtJsT1ZNB70txuNmwoBXWkkYbQW8KnGp3500slEFvtA.ucKLx5j9i2FWPQK5BcEdIKHz_mU0D7FEFZF9otHpIng&dib_tag=se&keywords=zero+to+production+in+rust&qid=1768950874&sprefix=zero+to+p%2Caps%2C109&sr=8-1) by Luca Palmieri.

### Description
This is an email newsletter implemented in Rust, with full test coverage including both unit and integration tests.  
Additionally, you can find a basic specification for deployment on DigitalOcean in the `spec.yaml` file.

### Getting Started

#### Clone repository

```sh
git clone https://github.com/letv1nnn/email-newsletter.git
cd email-newsletter
```

```sh
lua ./scripts/load_authorization_token.lua [token] # YOUR TOKEN
```

#### Build & Run

```sh
lua ./scripts/build.lua release
./target/release/zero2prod
```

#### Testing

Init database
```sh
sh ./scripts/init_db.sh
```

Run tests
```sh
lua ./scripts/build.lua test
```