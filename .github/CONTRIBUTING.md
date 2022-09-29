# How to contribute

First off, thanks for taking the time to contribute! 🎉🎉👍

## You know a client or mod that isn't on our list ? 📝

Open a new Github [issue][issue-link] or [pull request][pulls-link]
with your suggestion. Ensure the issue description accurately 
point out the name, link, features, language and development 
status of the client or mod if applicable.

Please be aware of the following things when making suggestions:

1. **Avoid making duplicate suggestions**. *Please* use the GitHub issue search 
   feature to check if your proposition has been mentioned in the past. 
   Duplicate issues are a huge maintenance burden on the limited resources 
   of the project. If it is clear from your report that you would have 
   struggled to find the original, that's ok, but if searching for a selection 
   of words in your issue title would have found the duplicate then the 
   issue will likely be closed extremely abruptly.

2. Make sure that the information you provided is accurate and if the
   project does not says it's archived or discontinued, it will be
   marked as on hiatus. 👍

> **:fire: Important:**
> All of the entries are ordered alphabetically. 
> Hence, while contributing, make sure to order to add the new 
> entry in an alphabetical order.

## What if a language is missing from our [badges list](/badges.md) ?

Just as the clients and mods, you can open a new Github [issue][issue-link] 
or [pull request][pulls-link] with your suggestion.

1. Copy this markdown 👇:
   - Table line: ```| <name> | [![<name>][<name>-Badge]][<name>-Url] | `[![<name>][<name>-Badge]][<name>-Url]` |```
   - Link references:
```
[<name>-Badge]: <badge link>
[<name>-Url]: <wikipedia page> "<name>"
```

2. Replace the following: 
   - `<name>`: The language name (i.e. Python)
   - `<badge link>`: The markdown badge link from [Ileriayo/markdown-badges](https://github.com/Ileriayo/markdown-badges) (i.e. https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
   - `<wikipedia page>`: The wikipedia page of the language (i.e. https://en.wikipedia.org/wiki/Python_(programming_language))

3. Add the table line to [badges.md](/badges.md), and make sure to put it in the right alphabetical position.

4. Add the link references at the end of [badges.md](/badges.md) and [README.md](/README.md), and also make sure to position it alphabetically.

---

##### Thanks! again to ALL the [amazing contributors!][contributors] 🙏

[issue-link]: https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties/issues
[pulls-link]: https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties/pulls
[contributors]: https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties/graphs/contributors
