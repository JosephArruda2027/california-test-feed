# California Test Show

A made-up podcast feed for testing the PODCASTS app in California (a TV app for a family PC).
**It is not a real show.** It contains only tones made by `make_feed.py`, and it is marked so podcast
directories don't list it (`itunes:block`, `podcast:locked`).

- Feed: https://josepharruda2027.github.io/california-test-feed/feed.xml
- Three episodes of 2 minutes. A click every 10 seconds makes a 30-second skip easy to hear; three
  beeps mark the end. Episode 3 has a chapters file with three chapters (Start 0:00, Middle 0:40, End 1:20).
- To remake everything: `python make_feed.py` (the cover picture was drawn separately).

Everything in this repository is dedicated to the public domain under CC0 1.0 (see `LICENSE`).
