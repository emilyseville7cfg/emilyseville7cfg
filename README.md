# 💕 Unbelievable Mystery 💕 [`🇺🇸 English`](https://github.com/EmilyGraceSeville7cf/markdown-library-english) [`🇮🇹 Italian`](https://github.com/EmilyGraceSeville7cf/markdown-library-italian)

<div align="center">

[![ubuntu](https://img.shields.io/badge/Ubuntu-cc4e0a?logo=ubuntu&logoColor=white)](https://discourse.ubuntu.com/u/emilygraceseville7cf/summary)
[![gnome](https://img.shields.io/badge/Gnome%20DE-059c9e?logo=gnome&logoColor=white)](https://discourse.gnome.org/u/emilygraceseville7cf/summary)
[![kde](https://img.shields.io/badge/KDE%20Plasma%20DE-05639e?logo=kde&logoColor=white)](https://discuss.kde.org/u/emilygraceseville7cf/summary)
[![flathub](https://img.shields.io/badge/Flathub-ffffff?logo=flathub&logoColor=black)](https://discourse.flathub.org/u/emilygraceseville7cf/summary)
[![lutris](https://img.shields.io/badge/Lutris-d17b0a?logo=lutris&logoColor=white)](https://forums.lutris.net/u/emilygraceseville7cf/summary)
[![hugo](https://img.shields.io/badge/Hugo-eb1ca6?logo=hugo&logoColor=white)](https://discourse.gohugo.io/u/emilygraceseville7cf/summary)

[![element](https://img.shields.io/badge/Element-@emilygraceseville7cf:matrix.org-0DBD8B?logo=element&labelColor=454545&logoColor=white)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/no-profile-link-supported.md)
[![bluesky](https://img.shields.io/badge/Bluesky-0285FF?logo=bluesky&logoColor=white)](https://bsky.app/profile/emilyseville7cf.bsky.social)
[![pinterest](https://img.shields.io/badge/Pinterest-e00b21?logo=pinterest&logoColor=white)](https://ca.pinterest.com/EmilyGraceSeville7cf/)
[![facebook](https://img.shields.io/badge/Facebook-0b4ee0?logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=61567348637149)
[![quora](https://img.shields.io/badge/Quora-c71a45?logo=quora&logoColor=white)](https://www.quora.com/profile/Unbelievable-Mystery?ch=3&oid=2302137716&share=e8798b79&srid=35tvcV&target_type=user)

![whatsapp](https://img.shields.io/badge/+7%20999%20808%2009%2030-10B418?logo=whatsapp&logoColor=white)

**Google Chat** messenger is the recommended way to contact me, while **Bluesky**
to view my updates.

> 🌴 **Facebook** and **Quora** are used through VPN and rarely.

</div>

## 📖 About me

I am open source contributor and I am keen on administrating, scripting,
creating sites and presentations. It’s my life. I like to automate routine tasks
and not to do them manually. Currently I have the skills mentioned below (just
the most interesting tools are mentioned and some of their usages are explained).

### :computer: Programming, markup and configuration languages

- :hammer_and_wrench: Developing CLI, TUI and GUI applications, automating tasks
  for developed tools:
  - `Go` ([`💬`][go_community]
[`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/go-tools-use))
  - `Fish` ([`💬`][fish_community]
[`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/fish-use)
[`📦`](https://github.com/fish-shell/fish-shell/pulls/EmilyGraceSeville7cf))

- :hammer_and_wrench: Developing VS Code extensions and Web Apps:
  - `JavaScript` ([`💬`][javascript_community]
  [`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/javascript-tools-use))

- :hammer_and_wrench: configuration languages for applications:
  - `YAML`
  - `JSON` ([`📦`](https://github.com/SchemaStore/schemastore/pulls/EmilyGraceSeville7cf))

- :hammer_and_wrench: Explaining developed tools:
  - `Markdown`

### :memo: IDEs and editors

- :hammer_and_wrench: Programming, writing tool explanations and
  configurations:
  - `Visual Studio Code` ([`💬`][vscode_community])

- :hammer_and_wrench: Drawing images for developed tools:
  - `Inkscape` ([`💬`][inkscape_community])
  - `GIMP` ([`💬`][gimp_community])
  
- :hammer_and_wrench: Creating presentations:
  - `OnlyOffice` ([`💬`][onlyoffice_communiy])
  - `Google Slides` ([`💬`][slides_community])
  - `Microsoft PowerPoint` ([`💬`][powerpoint_community])

### :clock130: VCS-tools

- :hammer_and_wrench: Managing tool development:
  - `Git`
  - `GitHub`

### :bookmark_tabs: Legend

- `💬`: community
- `⭐`: favorite tools
- `📦`: pull requests
- `🖊️`: personal scripts

[fish_community]: https://matrix.to/#/#fish-shell:matrix.org
[gimp_community]: https://discuss.pixls.us/tag/gimp
[go_community]: https://forum.golangbridge.org/
[javascript_community]: https://www.sitepoint.com/community/c/javascript/33
[inkscape_community]: https://inkscape.org/forums/
[vscode_community]: https://github.com/microsoft/vscode-discussions/discussions
[slides_community]: https://support.google.com/docs/threads?hl=en&thread_filter=(category:docs_slides)&sjid=18016765158418257400-EU
[onlyoffice_communiy]: https://forum.onlyoffice.com/
[powerpoint_community]: https://answers.microsoft.com/en-us/

<div align="center">

![gopher](./animated-jumping-gopher.gif)

</div>

## :notebook: Placeholder syntax in my CLI tools

Starting from 21 August 2024 I use the following placeholder syntax in all my
tools ([Go-inspired](https://pkg.go.dev/text/template)):

- `{{placeholder}}`: some arbitrary text with no constraints implied which
  should be exactly one CLI argument.
- `{{placeholder ...}}`: almost the same thing as the previous one, but here
  zero or more arguments are expected.
- `|` can be used inside double curly braces to provide more than one
  alternative for what can be placed instead of placeholder.

, where instead of `placeholder` any text can be written which explains what
should be put instead of CLI argument(s), but without spaces unless it's
explicitly permitted. This syntax is used just when no other default syntax is
mandated.

Examples:

```fish
command {{number}} # 1 number expected
command {{number..}} # 0 or more numbers expected
command {{number|strings...}} # one number or 0 or more string expected
```
