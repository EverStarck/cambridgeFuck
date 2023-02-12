<img width="100%" src="https://user-images.githubusercontent.com/51029456/218335736-87dbb76d-2b45-45d7-93af-7b68c55d8231.svg"/>

---

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />

  <h3 align="center">Cambridge Fuck</h3>

  <p align="center">
    Get the answers from the assignments of the platform
    <a href="https://www.cambridgeone.org">cambridgeone</a>
    <br />
    FOR EDUCATIONAL PURPOSE ONLY
    <br />
    <br />
    <a href="https://github.com/EverStarck/cambridgeFuck"><strong>Give the project a star!</strong></a>
    <br />
    <br />
    <a href="https://github.com/EverStarck/cambridgeFuck/issues">Report Bug</a>
    ·
    <a href="https://github.com/EverStarck/cambridgeFuck/issues">Request Feature</a>
  </p>

## The Project

Here is how it looks like:
| Script | Platform |
| --------------------------------------------------- | ---------- |
| ![Cambridge Fuck Script](https://user-images.githubusercontent.com/51029456/218334935-80a0aff7-c249-4e5b-87af-c060e3f6e7ab.png) | ![Cambridge One Platform](https://user-images.githubusercontent.com/51029456/218334976-cfe0bdcb-7061-467d-abee-31ad1d0a38c8.png) |

### Main modules

- [requests](https://docs.python-requests.org/en/latest/)
- [colorama](https://pypi.org/project/colorama/)
- [re](https://docs.python.org/3/library/re.html)
- [html](https://docs.python.org/3/library/html.html)
- [json](https://docs.python.org/3/library/json.html)

## Usage of the script

So easy, just follow the next steps:

### Getting the URL

1. Go to the assignment you want to get the answers
2. Open the developer tools
3. Go to the network tab
4. Search for the request that has the file `data.js`. It's possible you have to refresh the page.
5. Copy the URL of the request

![Getting the URL](https://user-images.githubusercontent.com/51029456/218335492-e1649e05-a597-4f5a-ace0-df1262d24f00.png)

### Running the script

1. Clone the repo

```sh
git clone https://github.com/EverStarck/cambridgeFuck.git
```

2. Install the dependencies

```sh
pip install -r requirements.txt
```

3. Run the script

```sh
python main.py <url>
```

## Understanding the script
`[?]` is the question

`[=]` is the answer

Please note that the script is not foolproof and **some questions may not be parsed accurately**. As a result, you may encounter incomplete questions or HTML tags in the text.

Example:
```
 ___ the nurses when they make mistakes. Thats hurtful to them, and it wont help them learn.___<strong>B:</strong> OK, Ill try not to say anything mean about them.
```

### The answer is a number?
Yes, it represents the index of the correct answer in the list of options. Please note that the numbering starts from 0.

![Droplist](https://user-images.githubusercontent.com/51029456/218336176-a7863483-40e9-4bab-9b4a-6682ec3b1dd1.png)

## Getting errors?
Sorry for that. Please open an issue and I will try to fix it as soon as possible.
Please make sure to include the URL.

<!-- CONTRIBUTING -->

## Contributing

Wanna contribute to the project? Great! Please follow the next steps in order to submit any feature or bug-fix.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat:Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

⚠️ Make sure to follow the [Commitizen](https://commitizen.github.io/cz-cli/) style, otherwise I will not accept your PR.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/EverStarck/cambridgefuck.svg?style=for-the-badge
[contributors-url]: https://github.com/EverStarck/cambridgeFuck/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/EverStarck/cambridgefuck.svg?style=for-the-badge
[forks-url]: https://github.com/EverStarck/cambridgeFuck/network/members
[stars-shield]: https://img.shields.io/github/stars/EverStarck/cambridgefuck.svg?style=for-the-badge
[stars-url]: https://github.com/EverStarck/cambridgeFuck/stargazers
[issues-shield]: https://img.shields.io/github/issues/EverStarck/cambridgefuck.svg?style=for-the-badge
[issues-url]: https://github.com/EverStarck/cambridgeFuck/issues
