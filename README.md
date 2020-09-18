# IPL Score 🏏

Cricket API for Get the Live IPL Cricket Score from espncricinfo.com.

> Simple Scrape Method to Fetch the Live Cricket Score from espncricinfo.com

## Methods Used ⚙

- PHP cURL - Read the Page Content
- `preg_match` - Scrape the Data

## Requirements

- PHP 7.2 or 7.3 or 7.4
- PHP cURL
- Server with PHP Support
- Works with Apache2, Nginx and Lightspeed
- SSL for Secure Connections

## API 🍔

- Get the Live Score Page URL score from - `https://www.espncricinfo.com/scores`

```html
/api.php?url=https://www.espncricinfo.com/series/8048/game/1216492/mumbai-indians-vs-chennai-super-kings-1st-match-indian-premier-league-2020-21
```

- Get Output in JSON Format

```json
{
    "success": true,
    "livescore": {
        "score": "Mumbai Indians vs Chennai Super Kings 1st Match Match Details, Schedule"
    }
}
```

## Usage 🍕

- Download this Repo or Public Folder
- Update the Live Match URL in `/assets/js/score.js`

> This is Example site and For My Personal Use you can Feel Free to Edit or Modify the Site

## Development 🍯

```sh
git clone https://github.com/mskian/iplscore.git
cd iplscore # for test the API
cd public # Modify the site
```

**Stay tuned for More Updates 😉**

## LICENSE ✅

MIT