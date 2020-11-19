# LimitOrderBook (WIP)
Attempts to implement an efficient and consistent (Limit Order Book)[https://github.com/JuliaFinance/Roadmap/issues/17] along with
a matching engine.

## Purpose
This is a generic LimitOrderBook that can be used to reconstruct tick and quote data
from granular data streams or historic data. It is also efficient enough for simulations
or consistency checking between multiple trade engines marshalling orders from rule engines.

