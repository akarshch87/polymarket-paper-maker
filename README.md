# Polymarket Paper Market Maker

A Python research simulator for studying market making with public market data and fictional trading sessions. It replays order books and trades, produces inventory aware quotes, simulates fills, and reports paper performance.

The replay includes cash and inventory limits, queue position estimates, fee assumptions, and tick size changes. Seeded studies compare a midpoint strategy with an inventory aware strategy across balanced and adverse fictional order flow. The results depend on the generated data and execution assumptions.

Download and extract `polymarket-source.zip` for the source, setup instructions, tests, and study. The project does not place live orders or access a wallet.
