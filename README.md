| :warning: Note - Fork of abandoned repository |
|:----------------------------------------|
| This is the a fork of [this repository](https://github.com/peterkahl/country-code-to-emoji-flag) which was neglectfully abandoned by the original author. |

# Country Code 🔡 ➡️ Emoji Flag 🇬🇧

Converts a country code to emoji flag. Most flags use a 2-letter code, but some use more (eg England=gbeng, Scotland=gbsct, Wales=gbwls, etc).

## Example in action: Screenshot of emoji flags inside phpmyadmin table.
![image](https://github.com/bobdenotter/country-code-to-emoji-flag/blob/main/screenshot-phpmyadmin-flags.png "Screenshot of emoji flags inside phpmyadmin table.")

## Example in action: Screenshot of a terminal window displaying a plain text log file.
![image](https://github.com/bobdenotter/country-code-to-emoji-flag/blob/main/logfile-example.png "Screenshot of a terminal window displaying a plain text log file.")

## Why Emoji❓
Emoji symbol is a textual replacement for a graphic image file while having the benefits of a graphic image. The image file is already present at your intended destination (a person's device), so why would you transmit the image to them again and again? -- Use emoji!

## ♻️Green Technology♻️
An image file equivalent to an emoji symbol may be tens, hundreds of kilobytes in size, while an emoji symbol is only several bytes. That's a bandwidth saving of around 10,000 times. If you use emoji instead of image files, you reduce your carbon footprint.

## Plain Text Is Now 😎Faux Rich Text
Now you can include emoji in plain text files, even in plain text emails, making them sharp, colourful and rich looking. You can put emoji flags into your database too!

## Emoji support: 🖥platform- and 🌍location-dependent‼️
Not every platform supports emoji. Therefore, use with caution! To my knowledge, iOS, macOS, Android are capable of displaying emoji. Additionally, some platforms (or geographical regions) may not be able to display certain flags. If unsure, use this as a reference and easy way to test your platform: <http://unicode.org/emoji/charts/full-emoji-list.html>

```php
use peterkahl\flagMaster\flagMaster;

echo flagMaster::emojiFlag('uk');    # 🇬🇧
echo flagMaster::emojiFlag('gbwls'); # 🏴󠁧󠁢󠁷󠁬󠁳󠁿
echo flagMaster::emojiFlag('gbsct'); # 🏴󠁧󠁢󠁳󠁣󠁴󠁿
echo flagMaster::emojiFlag('gbeng'); # 🏴󠁧󠁢󠁥󠁮󠁧󠁿

```
