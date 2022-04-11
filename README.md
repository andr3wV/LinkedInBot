# LinkedIn Connection Bot
I don't want to do homework, so here's what I cooked up. 

Just run it from your terminal or command prompt. The LinkedIn maximum connections per day is **80 to 100** and once that limit is exceeded you will be banned for a week from making connections; however, I personally have found that I can hit around 175 connection requests before being limited for only about a day. **Use at your own risk**, although there isn't that much!

> A tool to automate the connection requests on LinkedIn.

## Requirements

 - `node` 4.0.0 or greater
- `npm` latest version

**Note**: Install the latest version `node` and `npm` from [here](https://nodejs.org/en/download/).

## Install

Installs the two binaries`LinkedInBot` and `lab` to your system path using `npm`:

```bash
$ npm install -g linkedin-auto-bot
```
**Note**: you may have to force permissions (e.g. `sudo` on MacOS)


## Running

Use it as follows using `lab` command:

```bash
$ lab -u <your_linkedin_email> -k <keyword  Full Stack Developer>
```
**keyword Argument: enter a specific industry, company, or role (like Blockchain Researcher, Full Stack Developer, or JP Morgan); otherwise "ALL" will send connections requests to people you may know.** 

**Note**: Your login details are held locally and are not at risk. 

### I sincerely hope that this somehow gets you a job or something! 

