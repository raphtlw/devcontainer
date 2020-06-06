FROM debian:latest

# Install packages
RUN apt-get -qq update && apt-get -qq install \
git zsh curl

# Setup shell
RUN curl -fsSL https://starship.rs/install.sh | zsh -s -- --yes
RUN printf 'eval "$(starship init zsh)"' >> '/root/.zshrc'