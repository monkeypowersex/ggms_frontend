# GGMS_FE

## version
- `node` 16.13.1
- `npm` 8.1.2

## nvm setup

Windows일 경우 다음 링크에서 `nvm-setup.zip` 다운로드

[https://github.com/coreybutler/nvm-windows/releases](https://github.com/coreybutler/nvm-windows/releases)

### Install homebrew
```shell
xcode-select --install
```
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install nvm
```shell
brew install nvm
```

nvm 디렉토리 생성
```shell
mkdir ~/.nvm
```

터미널 설정에 맞춰 vi 편집기로 `~/.bashprofile` 또는 `~/.zshrc` 파일 열기
```shell
vi ~/.bash_profile
vi ~/.zshrc
```

아래 코드 입력 후, `esc` + `:wq` 명령어로 저장
```shell
export NVM_DIR="$HOME/.nvm"
   [ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"
   [ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && . "/usr/local/opt/nvm/etc/bash_completion.d/nvm"
```

변경 사항 적용
```shell
source ~/.bash_profile
source ~/.zshrc
```

### Use nvm
```shell
nvm install 16.13.1
```
```shell
nvm use 16.13.1
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).