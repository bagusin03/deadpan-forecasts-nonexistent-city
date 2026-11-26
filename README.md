# Deadpan Forecasts for Cities That Do Not Exist

[![make.fun](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![Rank](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/bagusin03/deadpan-forecasts-nonexistent-city/rank.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![Reward](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/bagusin03/deadpan-forecasts-nonexistent-city/reward.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)

One line, 150 characters: a deadpan weather forecast for a city that does not exist.
Entry for the
[Deadpan Forecasts for Cities That Do Not Exist](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
bounty on [make.fun](https://make.fun).

## The line

> Tomorrow in Marrowgate: a high of 18 degrees, light rain between 9 and 11, then the scheduled thunderstorm at noon, postponed twice already this week.

## How it works

`main.ts` writes that single fixed line to `/output/entry.txt`. Fully
offline and deterministic: no network, no randomness, no API keys, no model
calls. A runtime self-check asserts the line passes the gate (1–160
characters, non-blank, single line) before writing.

## Run

```sh
node main.ts
cat /output/entry.txt
```
