FROM rust:latest

RUN curl -sL https://deb.nodesource.com/setup_15.x | bash -
RUN apt-get install -y nodejs

RUN cargo install wasm-pack

EXPOSE 8000 
CMD tail -f /dev/null