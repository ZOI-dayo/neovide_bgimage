# Neovide

> # Neovide BGImage Fork
> 
> このレポジトリでは、オリジナルのNeovideの機能に加えて、背景画像を付けられるようになっています。
> 最低限使えるようにはなっているものの、ほぼ自分用に作ったものであるため、パフォーマンス等の問題が残っている可能性があります。
> それでも構わない方は利用してください。
>
> 以下のように設定を行なってください。
> ```lua
> g.neovide_background_image_path = "/path/to/image.png" -- /から始まるフルパス。JPEGなど、基本的なファイルなら指定可能です。
> g.neovide_background_image_transparent = 0.25          -- 背景画像の濃度。デフォルトで0.25です。
> ```

[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://discord.gg/SjFpZdQys6) [![Chat on Matrix](https://matrix.to/img/matrix-badge.svg)](https://matrix.to/#/#neovide_community:gitter.im) [![Discussions](https://img.shields.io/badge/GitHub-Discussions-green?logo=github)](https://github.com/neovide/neovide/discussions)

<img align="left" src="website/docs/assets/neovide-128x128.png">

This is a simple graphical user interface for [Neovim](https://github.com/neovim/neovim) (an
aggressively refactored and updated Vim editor). Where possible there are some graphical
improvements, but functionally it should act like the terminal UI.

To checkout all the **cool features**, **installation instructions**, **configuration settings** and
much more, head on over to [neovide.dev](https://neovide.dev).

<br>

<div align="center">
    <img src="website/docs/assets/BasicScreenCap.png" alt="Screenshot of Neovide">
    <em>Screenshot of Neovide running on Windows</em>
</div>

## Author Notes

I've been using this as my daily driver since November 2019. It should be relatively stable, but I'm
still working out some kinks and ironing out some cross platform issues. In general it should be
usable at this point, and if it isn't I consider that a bug and appreciate a report in the issues!
Any help and ideas are also greatly appreciated.

I'm also very interested in suggestions code quality/style wise when it comes to Rust. I'm pretty
new to the language and appreciate any critiques that you might have to offer. I won't take all of
them, but I promise to consider anything you might have to offer.

## License

Licensed under [MIT](./LICENSE).
