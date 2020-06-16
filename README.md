# wineapp
App to find the best wine at the market.

## What?
WineApp is an iPhone app that helps you find the best wine at the supermarket. While other wine apps require scanning individual bottles to get a rating, WineApp allows you to snap a picture of an entire shelf of wine bottles and it tells you which wine is the best. No more guessing based on winery name and year. It's like have your own personal sommelier right in your pocket.

## Who is it for?
This app is for anyone who wants to buy the best tasting wine within their budget, but aren't wine experts or afficianados.

## Technical - high level
1. Open WineApp. Take a photo of a shelf of wine bottles. Specify a budget if you wish.
2. WineApp figures out exactly what wine (brand, vineyard, variety, year, etc.) each bottle is, creates a list of wines.
3. WineApp searches a ratings database. It collects the ratings for each of the wines in the list.
4. WineApp ranks the list from best rated, descending.
5. WineApp presents the top rated wines to the user.

## Technical - details
The crux of the challenge comes from recognizing wines from a photograph. We anticipate using several techniques to best achieve this recognition.

1. Object recognition to isolate individual bottles.
2. Recognition within a bottle
  1. OCR to read the text. Any information that is present on a label including wine name, vineyard name, wine type, etc.
  2. Bar code.
  3. Images can point to a brand, possibly other information.

## Prior art
https://www.tomsguide.com/best-picks/best-apps-for-wine-lovers
https://www.digitaltrends.com/home/the-best-wine-apps-according-to-a-wine-pro/

## Technology considerations
* Object recognition - wine bottle, wine label
* Image recongnition - Logos, pictures on label
* OCR - words on label

## Use case
Before heading to a friend's dinner party you stop by the supermarket to pick up a bottle of wine. Hundreds of bottles stand before you, and you are lost. "Which $20-$25 bottle of wine is the best?" Your launch WineApp, open its viewfinder, snap, and it gives you a list of the best wines for the best price. Prepare to be the bringer of the finest vintage.
