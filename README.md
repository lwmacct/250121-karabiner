## 语雀文档 [Karabiner-Elements](https://www.yuque.com/lwmacct/macos/karabiner)

```bash
#!/usr/bin/env bash

__main() {
  cd ~/.config/karabiner || return 1
  rm -rf assets
  git clone https://github.com/lwmacct/250121-karabiner.git
  mv 250121-karabiner assets
}

__main

```