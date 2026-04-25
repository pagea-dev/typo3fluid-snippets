# TYPO3 Fluid Snippets Extension

Fluid Snippets provider for [TYPO3 Fluid](https://docs.typo3.org/other/typo3fluid/fluid/main/en-us/) ViewHelpers in VSCode and VSCodium.<br>
If you want to provide your own templates, [create a Pull Request via GitHub](https://github.com/pagea-dev/typo3-fluid-snippets/pulls)<br>
If you want have problems or ideas, [write an Issue via GitHub](https://github.com/pagea-dev/typo3fluid-snippets/issues)<br>
You can find the source code on [GitHub](https://github.com/pagea-dev/typo3-fluid-snippets)

## Features

All snippets are available in both **tag syntax** and **inline syntax**.

| Prefix | ViewHelper |
|---|---|
| `fAlias` | `<f:alias>` |
| `fAssetCss` / `fAssetCssInline` | `<f:asset.css>` |
| `fAssetScriptFile` / `fAssetScriptInline` | `<f:asset.script>` |
| `fBase` | `<f:base>` |
| `fCacheDisable` | `<f:cache.disable>` |
| `fCacheStatic` | `<f:cache.static>` |
| `fCacheWarmup` | `<f:cache.warmup>` |
| `fCobject` | `<f:cObject>` |
| `fComment` | `<f:comment>` |
| `fCount` | `<f:count>` |
| `fCycle` | `<f:cycle>` |
| `fDebug` | `<f:debug>` |
| `fFlashmessages` | `<f:flashMessages>` |
| `fFor` | `<f:for>` |
| `fIfThenElse` / `fIf` / `fThen` / `fElse` | `<f:if>` |
| `fImage` | `<f:image>` |
| `fInline` | `<f:inline>` |
| `fLayout` | `<f:layout>` |
| `fSection` | `<f:section>` |
| `fRender` | `<f:render>` |
| `fSecurityIfAuthenticated` / `fSecurityIfAuthenticatedThenElse` | `<f:security.ifAuthenticated>` |
| `fSpaceless` | `<f:spaceless>` |
| `fSwitch` / `fCase` | `<f:switch>` |
| `fTranslate` | `<f:translate>` |
| `fVariable` | `<f:variable>` |
| `fForm` | `<f:form>` |
| `fFormButton` | `<f:form.button>` |
| `fFormCheckbox` | `<f:form.checkbox>` |
| `fFormHidden` | `<f:form.hidden>` |
| `fFormPassword` | `<f:form.password>` |
| `fFormRadio` | `<f:form.radio>` |
| `fFormSubmit` | `<f:form.submit>` |
| `fFormTextarea` | `<f:form.textarea>` |
| `fFormTextfield` | `<f:form.textfield>` |
| `fFormUpload` | `<f:form.upload>` |
| `fFormatBytes` | `<f:format.bytes>` |
| `fFormatCase` | `<f:format.case>` |
| `fFormatCdata` | `<f:format.cdata>` |
| `fFormatCrop` | `<f:format.crop>` |
| `fFormatCurrency` | `<f:format.currency>` |
| `fFormatDate` | `<f:format.date>` |
| `fFormatHtml` | `<f:format.html>` |
| `fFormatHtmlentitiesdecode` | `<f:format.htmlentitiesDecode>` |
| `fFormatHtmlspecialchars` | `<f:format.htmlspecialchars>` |
| `fFormatNl2br` | `<f:format.nl2br>` |
| `fFormatNumber` | `<f:format.number>` |
| `fFormatPrintf` | `<f:format.printf>` |
| `fFormatRaw` | `<f:format.raw>` |
| `fFormatStriptags` | `<f:format.stripTags>` |
| `fFormatUrlencode` | `<f:format.urlencode>` |
| `fLinkAction` | `<f:link.action>` |
| `fLinkEmail` | `<f:link.email>` |
| `fLinkExternal` | `<f:link.external>` |
| `fLinkPage` | `<f:link.page>` |
| `fLinkTypolink` | `<f:link.typolink>` |
| `fUriAction` | `<f:uri.action>` |
| `fUriEmail` | `<f:uri.email>` |
| `fUriExternal` | `<f:uri.external>` |
| `fUriImage` | `<f:uri.image>` |
| `fUriPage` | `<f:uri.page>` |
| `fUriTypolink` | `<f:uri.typolink>` |
| `fNamespace` | Fluid namespace attribute |
| `fhtml` | `<html>` with Fluid namespace |

Append `Inline` to any prefix for the inline syntax variant, e.g. `fIfInline` → `{f:if(...)}`.

## Requirements

- TYPO3 13 or higher
- VSCode `^1.90.0` or VSCodium equivalent

## Installation

### Via Open VSX (VSCodium)

Search for `TYPO3 Fluid Snippets` in the Extensions tab.

### Via Marketplace (VSCode)

Search for `TYPO3 Fluid Snippets` in the Extensions tab or install via:

```
ext install pagea-dev.typo3-fluid-snippets
```

### Manual (.vsix)

Download the latest `.vsix` from the [Releases](https://github.com/pagea-dev/typo3-fluid-snippets/releases) page and install via:

```
Extensions → ··· → Install from VSIX...
```

## Contributing

Pull requests are welcome. For larger changes please open an issue first.

1. Fork the repository
2. Create your branch: `git checkout -b feat/my-snippet`
3. Commit your changes: `git commit -m 'feat: add f:myViewHelper snippet'`
4. Push and open a Pull Request

## License

[MIT](LICENSE)

## Acknowledgements

Inspired by the original (but outdated) [typo3-fluid-snippets](https://marketplace.visualstudio.com/items?itemName=febley.typo3-fluid-snippets) extension by febLey.