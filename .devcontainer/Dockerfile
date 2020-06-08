FROM alpine:latest

# Install packages
RUN apk add git zsh curl

# Setup shell
RUN curl -fsSL https://starship.rs/install.sh | zsh -s -- --yes
RUN printf 'eval "$(starship init zsh)"' >> '/root/.zshrc'