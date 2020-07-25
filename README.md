<div align="center">

<img
  src="https://raw.githubusercontent.com/IlanCosman/tide-resources/master/images/logo.svg"
  alt="Tide Logo"
  width="450"
/>

<!-- 0 width spaces on the line below -->

[![ci_badge][]][actions] ​ [![fish_version_badge][]](#System-Requirements) ​ [![license_badge][]][license]

</div>

#

<img
   src="https://raw.githubusercontent.com/IlanCosman/tide-resources/master/images/header.png"
   alt="Configuration Wizard"
   width="50%"
   align="right"
/>

**A modern prompt manager for the [Fish][] shell.**

- **Configuration Wizard:** With four compelling styles and myriad options, you can have your out-of-the-box cake and customize it too.
- **Flexible:** One line, two line, powerline, all fine!
- **Multi-line right prompt:** Impress all your Fish friends with this alien technology.
- **Intelligent:** Shows relevant information at a glance, emphasizing important material.
- **Extensible:** Easily add prompt items by creating simple fish functions.

<br clear="right">

## Installation

### Prerequisites

- [Git][]
- [Fish][] ≥ 3.1
- A [Nerd Font][nerd fonts] installed and enabled in your terminal (for example the [reccomended font](#fonts)).

#### Source and run the install function

```console
curl -sL git.io/tide | source && tide_install
```

## Features

### Configuration Wizard

Type `tide configure` to open the the wizard in your terminal.

![configuration_wizard][]

### Multi-Line Right Prompt

> Fish can't do _that_ yet can it?

![multi-line_right_prompt][]

### Pure Emulation

Tide can easily produce the same prompt as [Pure][]. Type `tide configure` and select the Pure style.

![pure_emulation][]

Tide doesn't recognize Pure configuration parameters, so you'll need to use `set tide_cmd_duration_threshold 3000` instead of `set pure_threshold_command_duration 3`, etc.

Pure style is an exact replication of the Pure fish theme and therefore displays less information than Lean. It exists only to ease the migration for users of that theme. Unless you are one of them, choose Lean style over Pure.

### Extensible

If there isn't a prompt item that fits your needs, make your own!

![extensible][]

## Documentation

See the [wiki][] for the boring parts of the documentation.

## Contributing

If you're interested in helping contribute to Tide, please take a look at the [Contributing Guide][].

## Fonts

### Meslo Nerd Font

Gorgeous monospace font designed by Jim Lyles for Bitstream, customized for Apple, enhanced by André Berg, and finally patched by Roman Perepelitsa of [Powerlevel10k][] with scripts originally developed by Ryan McIntyre of [Nerd Fonts][]. Contains all the glyphs and symbols that Tide may need. Battle-tested in dozens of different terminals on all major operating systems.

### Font Installation

Download these four ttf files:

- [MesloLGS NF Regular.ttf][]
- [MesloLGS NF Bold.ttf][]
- [MesloLGS NF Italic.ttf][]
- [MesloLGS NF Bold Italic.ttf][]

Open each file and click "Install". This will make the `MesloLGS NF` font available to all applications on your system. Configure your terminal to use this font.

## Acknowledgments

- [Powerlevel10k][] - Inspired much of Tide's documentation, resources, ideas, and design.
- [Starship][] - Inspired elements of the documentation.

<!-- Alphabetical Reference Links -->

[actions]: https://github.com/IlanCosman/tide/actions
[ci_badge]: https://github.com/IlanCosman/tide/workflows/CI/badge.svg
[configuration_wizard]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/animations/configuration_wizard.gif
[contributing guide]: CONTRIBUTING.md
[extensible]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/images/extensible.png
[fish]: https://fishshell.com/
[fish_version_badge]: https://img.shields.io/badge/fish-3.1.0%2B-blue
[git]: https://git-scm.com/
[license]: LICENSE.md
[license_badge]: https://img.shields.io/github/license/IlanCosman/tide
[meslolgs nf bold.ttf]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/fonts/mesloLGS_NF_bold.ttf
[meslolgs nf bold italic.ttf]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/fonts/mesloLGS_NF_bold_italic.ttf
[meslolgs nf italic.ttf]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/fonts/mesloLGS_NF_italic.ttf
[meslolgs nf regular.ttf]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/fonts/mesloLGS_NF_regular.ttf
[multi-line_right_prompt]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/images/multi-line_right_prompt.png
[nerd fonts]: https://github.com/ryanoasis/nerd-fonts
[powerlevel10k]: https://github.com/romkatv/powerlevel10k/
[prompt_connection]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/images/prompt_connection.png
[pure]: https://github.com/rafaelrinaldi/pure
[pure_emulation]: https://raw.githubusercontent.com/IlanCosman/tide-resources/master/animations/pure_emulation.gif
[starship]: https://github.com/starship/starship
[wiki]: https://github.com/IlanCosman/tide/wiki
