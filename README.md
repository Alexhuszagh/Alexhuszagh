<div align="center">
  <img src="https://github.com/AlexHuszagh/AlexHuszagh/raw/main/VariableBarricade.png" alt="Variable Barricade with the guys around you." width="65%" height=65%">
</div>

## AI Coding Tools and Agents

I don't use AI coding agents for both ethical and technical reasons and neither should you.

1. Trained without user consent: these tools were trained on open-source codebases without the authorization of their users, and for GPL-licensed and proprietary projects, this raises both ethical and legal concerns. Companies like Microsoft and Adobe have altered their terms of use to coerce you into "accepting" training, which isn't reasonable consent and for mirrored projects, may never have been given to begin with.
2. Prioritizes focusing on high-level design while getting low-level details wrong: AI coding tools often get specific, technical details wrong, while looking "good-enough", so actually validating this code that it both is sound and solves the issue at hand requires more effort than benefit. It may be good for quick-and-dirty tasks, but for larger code bases, it produces mass quantities of slop.
3. Destroying the open-source ecosystem: open source work assumes good faith of contributors, knowledge of the code base, and effort made to create high-quality contributions. With AI agents, we're seeing a mass proliferation of low-quality PRs that seem reasonable ands make accepting the work of external contributors a net negative. We're already seeing AI agents attempt to [blackmail] volunteer contributors.
4. Hurting junior developers: many junior developers rely on Github as a public resume. With larger projects closing down the doors to external contributors, many up-and-coming developers cannot prove their technical competence, and hiring unproven junior developers has become more effort than its worth.
5. Accessibility and internet access: solving CAPTCHAs is practically impossible for anyone with disabilities or the elderly. Want to create a Github account? Congratulations, me, an able-bodied, young adult was barely able to solve the visual tests when helping an aquaintance. Want to change my Microsoft password due to security alerts? I was only able to pass the hearing tests.
6. Proliferation of scams: the low effort it takes to generate scams has made exploiting people, especially the elderly, very easy. The AI "revolution" so far has benefitted con artists and scammers more than anyone else.

[blackmail]: https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me/

Until alternatives to Microslop and Github exist, unfortunately, I will be still maintaining all my projects here.

## About Me

Just a former biologist who got bored enough with Excel to start writing scripts to automate that process. Next thing, I'm optimizing floating-point parsers cross-compiled to a Raspberry Pi. Thinking is overrated and we should do less of it.

All of my projects are done on my own time, and are not related to my day job, so I appreciate your understanding that reviewing and merging PRs and feature enhancements may take some time.
<!-- [Please](https://synthmedia.fr/edito/tribunes/lutilisation-des-agents-intelligents-est-un-suicide-professionnel/) -->
<!-- I find it ironic that Github's aggressive push of Copilot has destroyed Github as a public platform. -->

[![My Skills](https://skillicons.dev/icons?i=rust,python,cpp,docker,nodejs,typescript,qt,dotnet,cmake,selenium,vue,html,css,linux,bash)](https://skillicons.dev)

A few of my accomplishments:
- Author of the Rust core library float [parser][rust-lang-pr].
- Creator of [rust-lexical], which implements fast float parsing and writing algorithms, used in [jiter], [arrow], [rust-python], [databend], (formerly [polars]) and more.
- Designed the [digit comparison algorithm][digit-comparison] for unambiguous floating-point parsing for near-halfway cases, used in [fast float][fast-float] and [rust-lexical].
- Designed stylish, customizable light and dark Qt [stylesheets][breeze-stylesheets].
- Maintainer for [cross-rs], for minimal setup cross-compilation on Rust.
- Maintainer of a fork of [fast-float] with security patches, used in [polars] and more..
- is unable to think during the summer heat.

Some other notable projects using lexical or fast-float2 include:
- [hifitime]
- [merde]
- [noodles]
- [pagefind]
- [swc]
- [qlty]
- [GraphQL]
- [posixutils-rs]
- [jsonb]
- [boa]
- [qsv]
- [serde_json] (a minified, vendored version)

You can find public forks of all my repositories on [Gitlab].

[rust-lang-pr]: https://github.com/rust-lang/rust/pull/86761
[rust-lexical]: https://github.com/Alexhuszagh/rust-lexical
[digit-comparison]: https://github.com/fastfloat/fast_float/blob/main/include/fast_float/digit_comparison.h
[fast-float]: https://github.com/fastfloat/fast_float
[breeze-stylesheets]: https://github.com/Alexhuszagh/BreezeStyleSheets
[cross-rs]: https://github.com/cross-rs/cross
[jiter]: https://github.com/pydantic/jiter
[polars]: https://github.com/pola-rs/polars
[arrow]: https://github.com/apache/arrow-rs
[hifitime]: https://github.com/nyx-space/hifitime
[rust-python]: https://github.com/RustPython/Parser
[merde]: https://github.com/bearcove/merde
[noodles]: https://github.com/zaeleus/noodles
[databend]: https://github.com/databendlabs/bendsql
[pagefind]: https://github.com/CloudCannon/pagefind
[swc]: https://github.com/swc-project/swc
[qlty]: https://github.com/qltysh/qlty
[GraphQL]: https://github.com/hasura/graphql-engine
[posixutils-rs]: https://github.com/rustcoreutils/posixutils-rs
[jsonb]: https://github.com/databendlabs/jsonb
[boa]: https://github.com/boa-dev/boa
[qsv]: https://github.com/dathere/qsv
[serde_json]: https://github.com/serde-rs/json/tree/master/src/lexical
[gitlab]: https://gitlab.com/Alexhuszagh

## Stats

<p align="center">
    <a href="https://github.com/AlexHuszagh" style="width: 100%">
        <img src="https://github-readme-stats.vercel.app/api?username=AlexHuszagh&show_icons=true&theme=radical" alt="" height="160px"/>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlexHuszagh&layout=compact&theme=radical&langs_count=6" alt="" height="160px"/>
    </a>
</p>
