# [Russian Roulette](https://ministry-of-truth-1984.github.io/russian-roulette/)

A tool for estimating the odds to be a casualty invading Ukraine.
By explicitly listing our sources and breaking down the calculations, there is no trust requirement on the tool itself - it acts like a spreadsheet.
Users can override all inputs, so they need not trust any built-in sources and can merely use the tool for convenience.

## Contributing 

### Anonymity
If you want to contribute but fear detection/reprisals from state-aligned actors, consider using [Whonix](https://www.whonix.org/) and/or [Qubes](https://www.qubes-os.org/). Another alternative is [Tails](https://tails.boum.org/). For details see https://www.whonix.org/wiki/Comparison_with_Others

In either case, use different email/github accounts than your personal/professional ones.

### How you can help
* Double-check some calculations or the accuracy/legitimacy of provided sources. The more scrutiny, the better. Even if you can't implement things directly, reporting better values/sources/calculations is useful.
* If you notice an error or want to suggest an improvement, search the issues to see whether it's already been proposed. If you can quickly implement this, just send a PR, otherwise make an issue and state whether you'll work on it.
* If you want to help but have nothing specific in mind, check for unassigned [issues](https://github.com/ministry-of-truth-1984/russian-roulette/issues).
* To avoid duplication of work, check whether someone already started on an issue.
* To avoid stalling, issues might be re-assigned when they have no progress after a while, but we will aim for giving plenty of advance warning. The exact time will depend on priority/complexity of the change and amount of un-assigned work.
* Non localized changes (e.g. redesign) should get explicit approval in an issue so that only one of these is in flight at any moment, to avoid conflict overhead.
* If your change involves localizable text and you don't know how to translate it, mark your PR as a draft and make sure _Allow edits by maintainers_ is checked.

### Coding style
* Keep everything in the `index.html` file. This makes it easier to share with non tech savy people, especially if the repo/page stop being available.
* Only use attributes for styling. This minimizes non-local conflicts.

### Branching
PRs should target `develop`. The github page follows `main`. 
