FROM rust:1.65
COPY . /usr/src/basic-otlp/
WORKDIR /usr/src/basic-otlp/
RUN cargo build --release
RUN cargo install --path .
CMD ["/usr/local/cargo/bin/basic-otlp"]
