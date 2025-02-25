# 歡迎來到土地公 Quick start guides

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## 這是一段程式碼

以下是一段`Javascript`，請看：

```js
function hello () {
    console.log("您好");
}
// 呼叫hello函數
hello()
```

## 使用擴充模組 tab

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

  [Language]: changing-the-language.md
  [Navigation]: setting-up-navigation.md
  [Header]: setting-up-the-header.md
  [Footer]: setting-up-the-footer.md
  [Search]: setting-up-site-search.md
  [Tags]: setting-up-tags.md


### 使用tab
=== "分頁1"
    這是分頁一喔

=== "分頁2"
    這是分頁2喔