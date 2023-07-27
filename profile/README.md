# Hashids is moving 🧳

> **tl&dr:** Hashids is being upgraded & rebranded to [Sqids](https://sqids.org/).

Hashids is a small library that generates YouTube-looking IDs from numbers. By now, it supports implementations in many different programming languages. It has served the community well over the last few years & we believe we can improve it in a few ways:

## What is changing?

1. **Repos are now hosted in [one place](https://github.com/orgs/sqids/repositories).** That way it's easier to maintain & update code (existing repos stay where they are).
1. **Consistent IDs.** All supported programming languages produce the same IDs.
1. **Simpler algorithm.** The new algorithm produces better randomized IDs, while keeping implementation simple.
1. **Simplified API.** Only `encode` and `decode` functions w/ clear indication for the largest supported unsigned integer.
1. **No more salt.** Support for custom IDs is now done by providing a manually shuffled alphabet. This is an optional step.
1. **Profanity blocklist.** Support for blocking specific words from appearing in generated IDs. Libraries come with a basic default blocklist for several languages.
1. **Clear goals & examples.** More defined use-cases that emphasize what this library is good for (and not good for).
1. **New name.** No association with hashes anymore + shorter name.
1. **Updated [website](https://sqids.org/).** Now includes use-cases, playground, easier repo filtering, FAQs & features.
1. **Sponsor support.** To ensure that the project can be sustained for years to come.

## FAQs

### What is happening with existing repos?

Nothing. Existing implementations stay where they are. They have plenty of on-going usage & the new website links to them as well.

### Is the new algorithm a drop-in replacement for Hashids?

No. Sqids produces different IDs. We advise to use it only on new projects or if you are not using any pre-generated IDs.

### Has every existing language been upgraded to the new algorithm?

No. Upgrading repos is an on-going process. You can see the progress [here](https://github.com/orgs/sqids/repositories). If you'd like to [contribute to a new language or an existing repository](https://github.com/sqids/sqids-spec#-porting-to-a-new-language), please reach out to one of the maintainers.

### When can I start using Sqids?

Now. Some implementations have already been published.

### What's next?

- [x] Redirect `hashids.org` to `sqids.org`
- [ ] New [language repos](https://github.com/orgs/sqids/repositories) are being worked on

### Where can I find more info?

[Sqids website](https://sqids.org/) is a good starting place.