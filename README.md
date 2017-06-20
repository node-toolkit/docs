# Toolkit docs

> Documentation for the toolkit suite

_This **is not** how documentation will be organized on the actual documentation sites._

If you are working on the documentation site for assemble, you will only need the [assemble docs](src/content/building-blocks/assemble). If you get a `404` or nothing is there yet, that means we haven't collated the information yet (and check back frequently b/c we're working on that now).

## The goal

This repository is (probably) temporary, which we're using to collate and de-duplicate all of the documentation for all of the `toolkit` projects, including:

- [assemble][]
- [base][]
- [generate][]
- [templates][]
- [update][]
- [verb][]

By doing this, we will be able to streamline the information, and remove duplicate information in favor of cross-linking and cross-repo search.


## Collating docs

The documentation (in this repo, not the sites) should be roughly organized as follows:

- `_draft`: anything that isn't usable or close to usable. Might be notes, ideas, etc.
- `wip`: source markdown content that hasn't been reviewed yet
- `src`: has been reviewd and maybe re-written, de-duped with other collated docs, checked for grammatical errors, etc, and then organized into a specific folder.


```
 .
 ├── _draft
 ├─┬ src
 | └─┬ content
 |   ├─┬ automation
 |   | ├── Enquirer
 |   | ├── Microbot
 |   | └── Update
 |   ├─┬ configuration
 |   | ├── Boilerplate
 |   | ├── Scaffold
 |   | └── Snippet
 |   ├─┬ building-blocks
 |   | ├── Base
 |   | └── Templates
 |   ├─┬ lifecycle
 |   | ├── Assemble
 |   | ├── Generate
 |   | └── Verb
 |   └ data
 └── wip
```


[assemble]: https://github.com/assemble/assemble
[base]: https://github.com/base/node-base
[generate]: https://github.com/generate/generate
[templates]: https://github.com/jonschlinkert/templates
[update]: https://github.com/update/update
[verb]: https://github.com/verbose/verb