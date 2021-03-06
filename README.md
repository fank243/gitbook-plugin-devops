# gitbook-plugin-devops

A GitBook plug-in that supports multiple modules, the following modules are now supported

|      Module      |                                           Website                                            |
| ---------------- | -------------------------------------------------------------------------------------------- |
| Baidu Analytics  | [https://tongji.baidu.com](https://tongji.baidu.com)                                         |
| Google Search    | [https://www.google.com/webmasters/tools/home](https://www.google.com/webmasters/tools/home) |
| Google Analytics | [https://analytics.google.com](https://analytics.google.com)                                 |
| Livere Comment   | [https://livere.com](https://livere.com)                                                     |

## Install

Add the following configuration to `book.json`

```json
{
  plugins: ["devops"]
}
```

Execute the following command to install

```shell
gitbook intall ./
```

or

```shell
gitbook install gitbook-plugin-devops
```

## Settings

```json
"devops":{
    "bd_token":"25d234bbafdb7c9bc207310c9ca5efcb",
    "google_search":"your html meta tag content",
    "google_analytics":"UA-111740326-1",
    "livere_token":"MTAyMC8zMjk4MC85NTQy"
}
```

If you do not want to install a module, please do not set or leave blank

|      Setting       | IsNeed |          Description           |
| ------------------ | ------ | ------------------------------ |
| `bd_token`         | No     | Bai Analytics Token            |
| `google_search`    | No     | Google Search html tag content |
| `google_analytics` | No     | Google Analytics UA-ID         |
| `livere_token`     | No     | Livere Comment Token           |