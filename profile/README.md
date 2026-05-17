# OpenAfterHours

  > Open-source tooling for the regulatory work that protects the public but
  > rarely makes the slide deck — written by engineers, for engineers, in the
  > small hours.

  **Landing page** → [openafterhours.github.io](https://openafterhours.github.io)

  ## What we ship

  | Repo | What it does |
  | --- | --- |
  | [`rwa_calculator`](https://github.com/OpenAfterHours/rwa_calculator) | UK Credit Risk RWA engine for CRR (Basel 3.0) and Basel 3.1 (PRA PS1/26). Standardised, F-IRB, A-IRB, Slotting. Polars all the way down. |
  | [`moonlit`](https://github.com/OpenAfterHours/moonlit) | Bundle a uv-managed project — or a whole uv workspace — into a single self-contained zipapp per PEP 441. No installer, no host venv, just one `.pyz`. |
  | [`watchfire`](https://github.com/OpenAfterHours/watchfire) | Static analysis for UK financial regulatory citations in Python code. |

  ## Why we build this

  Regulation protects the public. It shouldn't cost the bank millions to comply.

  - **Open source by default.** Capital-adequacy code shouldn't be a black box.
    Every formula in the open, every assumption auditable, every result
    reproducible from the same lockfile.
  - **Lowest possible overhead.** Compliance work doesn't generate revenue —
    every hour spent on it is a tax on the bank. Polars and uv keep that tax
    small. Millions of exposures in seconds, not hours.
  - **Built after hours.** Maintained by engineers in the spare hours
    that don't belong to a quarterly cycle — which is, it turns out, exactly
    when good infrastructure tends to get written.

  ## Stack

  Python · Polars · uv · marimo · Apache 2.0

  ## Get involved

  Issues, discussions, and PRs welcome on any repo. If you've shipped this
  kind of code in a bank and want a place to do the open-source version,
  this is it.
