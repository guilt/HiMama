# himama: HiMama Downloader

Python/Selenium based utility in Python, to download 
pictures and videos offline.

# Dependencies

Install:

- Python 3.9 or Higher

# Installation

Run this in your Command Prompt or Terminal:

```shell
python -m pip install himama
```

Depending on which Operating System you use, the command could either be
`python3` or even `python3.9`.

Now download and install a supported WebDriver. Currently it
tries to use:

- Safari
- Firefox (Gecko)
- Edge
- Chrome
- Opera

but support may vary.

# Usage

To Download, run:

```shell
himama
```

To run non-interactively such as a Cron Script, set these variables
in your environment.

```shell
set HIMAMA_USER=daddy@daddy.com
set HIMAMA_PASSWORD=changeMe
```

It needs a non-headless mode, or a virtual display to run.

# Questions and Feedback

I wrote this in my spare time. All feedback and patches welcome.
