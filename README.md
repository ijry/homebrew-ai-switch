# homebrew-ai-switch

[AI Switch](https://github.com/ijry/ai-switch) 的 Homebrew tap。

```sh
brew install --cask ijry/ai-switch/ai-switch
```

`Casks/ai-switch.rb` 由 ai-switch 仓库的发布流水线生成并推送，请不要手工编辑——下一次发布会覆盖它。

安装包是 ad-hoc 签名、未经 Apple 公证，所以 cask 的 `postflight` 会清掉 Homebrew 加上的隔离属性，装完直接能打开，不需要在系统设置里手工放行。

---

Homebrew tap for [AI Switch](https://github.com/ijry/ai-switch).

```sh
brew install --cask ijry/ai-switch/ai-switch
```

`Casks/ai-switch.rb` is generated and pushed by the ai-switch release pipeline — do not edit it by hand, the next release overwrites it.

The bundle is ad-hoc signed and never notarized by Apple, so the cask's `postflight` clears the quarantine attribute Homebrew adds; the app opens straight after installing, with no manual Gatekeeper step.
