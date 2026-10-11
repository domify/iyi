# Proposal: rename the project to `cry` (file extension `.cy`)

Hi, and thanks for all the work on this fork!

A bit about me: before iyi I tried to make Crystal compile incrementally
with Opus 5.5 and Sol 6.1, in [an
incremental-compilation fork][ic]. I also concluded that Crystal's architecture
doesn't allow a proper solution, and found to iyi. Since then I've ported
[Slang](https://github.com/domify/slang) and
[TOML](https://github.com/domify/toml) to iyi, and I'm the author (with llms) of
[iyipacks-website](https://github.com/domify/iyipacks-website), which is built
on them. 

I'd like to propose a rename: **iyi → cry**, with source files ending in
**`.cy`** instead of `.iyi`.

**Why rename?** Turkish is a lovely language, and we should always be proud of
our culture and identity. I'm Estonian, so by the same logic I could have named
my own language *jää-äär* ;-)

But for others outside of Türkiye, the visitor tends to read the name as belonging
to a language made for one country, not to a general-purpose language for everyone.
It's also hard to say out loud. I tried telling friends about the project, and most of the
conversation was me explaining how to pronounce it, why we have to speak now Türkçe.

So I'm proposing **cry**: a shorter form of Crystal that keeps what the name
stands for, a very fast new language built on Crystal's heritage.

**Why cry.**

- **It's international and fun.** Anyone can say it, it's easy to remember, and
  it doesn't belong to any one country or language community.
- **It shows where it comes from.** `cry` / `.cy` sits right next to Crystal's
  `crystal` / `.cr`. You can feel at a glance that this is super fast a Crystal fork, 
  and a strong one.
- **It's short.** Three letters is nice for a CLI: `cry build`, `cry run`,
  `cry mod`.
- **It's an in-joke for Rubyists.** Plenty of Ruby on Rails friends are
  carefully learning Rust syntax right now, and they do cry, even DHH is cry-ing now ;-)
  A Ruby-flavoured, Crystal-based language called `cry` will make them smile and
  then maybe make them look.

I know a rename touches a lot: the binary, `.iyimod`, the samples, CI, install
scripts and the GitHub org. That's why it might be worth doing before the first
release, while it's still cheap. I'm happy to help with the mechanical part if
the maintainers like the idea.

If `cry` is taken or ruled out, my next choice would be `cris`, but I
personally love `cry`.

What do you think?

[ic]: https://github.com/priit/crystal/tree/incremental-compilation
