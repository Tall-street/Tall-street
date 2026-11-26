<img src="banner.png" alt="Tall Street. Take the street, one floor at a time. A daily tower game on Robinhood Chain." width="100%">

Tall Street is a daily tower game on Robinhood Chain. Crews stack floors on towers tied to stock tokens, each stock decides what its tower is worth, and at 20:00 UTC the most valuable street takes the pot.

### How a round works

- A round runs from 20:00 UTC to 20:00 UTC. Every tower starts empty.
- A floor costs 0.001 ETH, or 0.002 ETH in the final hour, from 19:00 to 20:00 UTC.
- The crew with the most floors on a tower holds it. A draw stays with whoever got there first.
- Each tower has a weight that follows its stock token: 1 + 10 × the move since the open, kept between 0.5 and 1.5.
- At the close, the crew with the highest street value wins. 90% of the pot goes to that crew, split by the floors each member placed. 10% goes to Tall Street.

### Status

- **The game is open** at [tallst.com](https://tallst.com) since 26 November 2026. Rounds are played with real ETH.
- **Game contracts:** source in [contracts](https://github.com/Tall-street/contracts), every contract verified on Sourcify with an exact match. Game `0xD96cb122028adBbe5e85C255598E66D2B9ab5999`, staking `0x21f36721dc6Ee094DB3Fb3A9b96147898D034548`. Not audited.
- **$TALL:** `0x4c5FF4029f581010bEF5709EC0b909584b129BFb`. Hold it to found a crew and place up to 100 floors at once; stake it for up to 20% off every floor. The address is also on [tallst.com/tall](https://tallst.com/tall).
- **Rules:** public in [rules](https://github.com/Tall-street/rules). The engine and tests the game contracts follow, with a plain-language spec.

Updates on X: [@TallStreetHQ](https://x.com/TallStreetHQ)
