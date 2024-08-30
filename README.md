# Beginning
This manual will help you to install fastfetch to your Windows machine

[![Russian](assets/ru.gif)](README_RU.md)

[1. Installing](#Installing)\
[2. Author's config](#Сonfig)\
[3. Aliases](#Alias)

# Installing
1. Install [scoop](https://scoop.sh/) on your machine
2. Enter the `scoop install fastfetch` command
3. Run `fastfetch`
4. Fastfetch installed!

![Fastfetch](assets/pic1.png)

# Сonfig
5. Download and install FiraCode fonts
6. Set this font in terminal

![FiraCode](assets/pic2.png)

7. Download the **swzxfetch.jsonc**, copy to C:\Windows
8. Run Fastfetch with command `fastfetch -c C:\Windows\swzxfetch.jsonc`
9. Profit!

![Fastfetch2](assets/pic3.png)

# Alias
10. Enter this command `notepad $profile`
11. Paste it - function n([Parameter(ValueFromRemainingArguments = $true)]$params) {\
    & fastfetch -c C:\windows\swzxfetch.jsonc $params\
} into notepad and save!

![Alias](assets/pic4.png)

12. Enter the `n` command




