# termux-neofetch
Neofetch but with the logo that is displayed when you open Termux instead of Android logo
![.](/screenshot.jpg) 

# Deprecation note:
Neofetch is no longer supported and I don't even use it anymore, I prefer fastfetch, to use it with fastfetch you simply need to copy the ascii file to ~/.ascii and configure it on your `~/.config/fastfetch/config.jsonc`:

```json
        "logo": {
                "color": {"1": "white"},
                "source": "~/.ascii",
                "padding": {
                        "top": 1
                }
        },
```
