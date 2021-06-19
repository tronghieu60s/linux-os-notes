# Các Ghi Chú Về WSL Terminal Windows.

## 1. Cài Đặt WSL

### 1. WSL2 - Linux trên Windows.

*Cài Đặt*:

1. https://www.youtube.com/watch?v=aIYhaeJa90g

2. https://docs.microsoft.com/en-us/windows/wsl/install-win10

### 2. Cài đặt ZSH - Ohmyzsh - Powerlevel10k

1. https://www.youtube.com/watch?v=jtk3Aw1wqRQ

2. https://haidnguyen.dev/en/setup-wsl2-for-web-development/

3. https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH#ubuntu-debian--derivatives-windows-10-wsl--native-linux-kernel-with-windows-10-build-1903

4. https://github.com/ohmyzsh/ohmyzsh#getting-started

5. https://github.com/romkatv/powerlevel10k#get-started

### 3. Cài đặt Zsh-Autosuggtestions

*Giải pháp*: https://viblo.asia/p/cach-cai-dat-zsh-va-zsh-autosuggestions-tren-ubuntu-LzD5ddDO5jY#_cai-dat-zsh-autosuggestions-3

*Cài đặt*: https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh

## 2. Thiết Lập Tiện Ích

### 1. Thêm theme cho giao diện Terminal.

*Giải pháp*: https://windowsterminalthemes.dev/

*Cài Đặt*: https://www.youtube.com/watch?v=mnWA4EP2Zhw

### 2. Thêm theme cho giao diện Terminal trong VSCode.

Sử dụng `Ctrl + Shift + P` sau đó tìm kiếm và mở `Preferences: Open Settings (JSON)` để tùy chỉnh giao diện:

Dưới đây là ví dụ về giao diện Dracula:

```js
"workbench.colorCustomizations": {
  /* ... */
  "terminal.selectionBackground": "#44475A",
  "terminal.foreground": "#FFFFFF",
  "terminal.ansiBlack": "#000000",
  "terminal.ansiBlue": "#BD93F9",
  "terminal.ansiBrightBlack": "#676E95",
  "terminal.ansiBrightBlue": "#82AAFF",
  "terminal.ansiBrightCyan": "#89DDFF",
  "terminal.ansiBrightGreen": "#50FA7B",
  "terminal.ansiBrightMagenta": "#BD93F9",
  "terminal.ansiBrightRed": "#FF5555",
  "terminal.ansiBrightWhite": "#FFFFFF",
  "terminal.ansiBrightYellow": "#F1FA8C",
  "terminal.ansiCyan": "#89DDFF",
  "terminal.ansiGreen": "#50FA7B",
  "terminal.ansiMagenta": "#BD93F9",
  "terminal.ansiRed": "#FF5555",
  "terminal.ansiWhite": "#FFFFFF",
  "terminal.ansiYellow": "#F1FA8C",
  "terminalCursor.background": "#000000",
  "terminalCursor.foreground": "#FFCB6B",
}
```

### 3. Mở một tab mới với đường dẫn giống với tab cũ.

*Giải pháp*: https://github.com/microsoft/terminal/issues/3158#issuecomment-832533906

*Cài Đặt*: https://github.com/kerol2r20/Windows-terminal-context-menu 
