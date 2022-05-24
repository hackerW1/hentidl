# hentidl-0.2-beta


it's a tool built in shell scripting which scrapes [nhentai.net](https://nhentai.net) and downloads all hentai managa in your local computer.
The tool is indie and very minimal with LOC < 130.
I just made it as a fun project. The idea came after ani-cli.
If you like this project please consider donating :D

---


# Table of Content

- [Installation](#Installation)
- [Usage](#Usage)
- [Notes](#Notes)
- [Contributors](#Contributors)
- [Donation](#Donation)
- [Dependencies](#Dependencies)

---


## Installation


### Linux

```sh
git clone https://github.com/hackerW1/hentidl
```


## Usage

```
./hentidl -t         [            tag search             ]

./hentidl -d <code>  [    download doujinshi of code     ]

./hentidl -s <query> [       search for doujinshi        ]

./hentidl -r         [ remove cachedir and all downloads ]

./hentidl -ssr       [      simple sequence renamer      ]
```

## Notes

[ssr: without ssr the sxiv image viewer won't work correctly]

[ssr: use hentidl in it's default directory if you are using ssr option]

[default-downloading-directory: ~/.cache/hentidl/downloads/]


## Contributors

- [hackerW1] : [telegram](https://t.me/ubun7uus3r), [github](https://github.com/hackerW1)


## Donation

- monero

44WXvNeQAvx1k4cQ2wHeVfCMVkN2eKRsndshWfi2qkfpiHuecumArA65gwoAzBMRV5J5Xo1zqi4YH6W2n7XXwM1LLtVNMrp


## Dependencies

- gnu-posix-tools -> html-parser 
- curl -> https-request-maker
- sxiv -> image-viewer
- aria2c -> download-manager

---
