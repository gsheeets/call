<h1 align="center" style="border-bottom: none">
  <a href="https://github.com/gsheeets/call">📞 Call</a><br>
  Smart Way to Make Phone Numbers Clickable in Google Sheets
</h1>
<p align="center">
  <a href="https://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
</p>

## The problem

[HYPERLINK()](https://support.google.com/docs/answer/3093313) is the function to create links, but it doesn't support (or offers) __tel:__ or __call:__ link protocoles.

## Workaround

### ~~First option~~

~~As describe in [Google Docs Editors Community](https://support.google.com/docs/thread/44648779?hl=en&msgid=44720782), you can use an add-on or use labnol third-party URL without knowing what is done with you info.~~

### BEST option

You can use **Gsheeets Call** page which contain nothing else but the redirection to the [tel protocol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#linking_to_telephone_numbers), you can check code [here](./404.html).

## Demo

Need some demo, check those links:
- [White House (US) - +1 202-456-1111](https://gsheeets.github.io/call/+1%20202-456-1111)
- [PM Office (India) - +91 (11) 2301 2312](https://gsheeets.github.io/call/+91%20(11)%202301%202312)
- [Google Support (US) - +1 855-836-3987](https://gsheeets.github.io/call/+1%20855-836-3987)
- [Microsoft (India) - 1-800 102 1100](https://gsheeets.github.io/call/1-800%20102%201100)
- [10 Downing St (UK) - +44 (20) 7925 0918](https://gsheeets.github.io/call/+44%20(20)%207925%200918)

## How to use

You just need to concatenate you phone number cell (here `A1`) with `https://gsheeets.github.io/call/` via an HYPERLINK function like this:

```
=HYPERLINK("https://gsheeets.github.io/call/"&A1; "Call our support team")
```

## Authors

- **Mehdi Chaouch** - *Maintainer* - [![GitHub followers](https://img.shields.io/github/followers/mehdichaouch.svg?style=social)](https://github.com/mehdichaouch)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) details.

## Credits

### Inspired by

This was designed with the inspiration from this fine folks:
- [labnol](https://www.labnol.org/internet/google-sheets-phone-numbers/29228/)
