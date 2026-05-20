# The Greeks and Hedging

Deck 07 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_07_Greeks_and_Hedging/

A guided tour of chapters 8 and 10 of *Paul Wilmott Introduces Quantitative
Finance* (2nd edition, Wiley, 2007) &mdash; the closed-form Black&ndash;Scholes
prices, the partial derivatives that traders live by, and how hedging actually
works in practice.

## What's inside

- The closed-form European call $C = S N(d_1) - K e^{-r\tau} N(d_2)$ and the put via parity
- Binary (digital) call and put formulas
- Delta $\Delta = N(d_1)$ &mdash; the hedge ratio
- Gamma $\Gamma = n(d_1) / (S \sigma \sqrt{\tau})$ &mdash; convexity, peaks at the money
- Theta $\Theta$ &mdash; time decay, and the BS PDE rewritten as $\Theta + \tfrac{1}{2}\sigma^2 S^2 \Gamma = r(V - SV_S)$
- Vega $\mathcal{V} = S \sqrt{\tau}\, n(d_1)$ &mdash; sensitivity to volatility, the vega&ndash;gamma relation
- Rho, speed, charm, colour, vanna, volga (a light touch)
- Implied volatility and the smile/skew preview (deck 08)
- Delta hedging in practice &mdash; discrete rebalancing, hedging-error scales as $\sqrt{\delta t}$, gamma and vega hedging, static vs dynamic
- **Interactive Greeks Explorer** &mdash; three subplots ($V, \Delta, \Gamma$ vs $S$), with sliders for $S, K, T, \sigma, r$ and a call/put toggle; live trader-quoted Greeks ($\Theta$/day, $\mathcal{V}$/vol-pt, $\rho$/rate-pt)

Companion to chapters 8 and 10 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
