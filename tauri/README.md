# Tauri

## Install
To install all dependencies needed for Tauri
```
# adapted from https://v2.tauri.app/start/

# install rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
> default
echo 'source "$HOME/.cargo/env' >> ~/.bashrc

# Additional tauri deps
dnf install webkit2gtk4.1-devel \
  openssl-devel \
  curl \
  wget \
  file \
  libappindicator-gtk3-devel \
  librsvg2-devel \ 
  nodejs
dnf group install "c-development"
npm install
```

## Development
```
cd tauri
npm install
npm run tauri dev
```
