# Where are Character.AI users going? Open data

The public data behind the report [Where are Character.AI users going?](https://amavie.ai/where-character-ai-users-go):
weekly US searches and daily app store ratings for Character.AI and the apps people name as alternatives, from before the
October 2026 bankruptcy filing to today.

Free to use under [Creative Commons Attribution 4.0](LICENSE.md): credit Amavie and link to the report.

## Files

| File | What it holds | Updated |
| --- | --- | --- |
| `data/search-us-weekly.csv` | Weekly impressions in Bing in the US for each phrase: `week_ending`, `phrase`, `searches_containing_phrase`, `exact_searches` | weekly |
| `data/app-ratings.csv` | Public rating counts and averages in the US App Store and Google Play: `captured_at_utc`, `store`, `country`, `app`, `rating_count`, `average_rating` | daily |

## How to read it

- Impressions count searches, not people, and Bing is a sample of US search, not all of it.
- New ratings stand in for new users: most people never rate an app, so compare apps with each other and with their own past.
- Bing revises recent weeks, so the search file is rewritten in full on every update.

## Cite as

Amavie, "Where are Character.AI users going? Search and app store data", https://amavie.ai/where-character-ai-users-go

## Who made this

We make [Amavie](https://amavie.ai), an app of AI characters and one of the apps people might move to. Amavie is not in the data.
The charts, the method and what we conclude from the numbers are in the report.
