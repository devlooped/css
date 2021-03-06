# Changelog

## [v1.0.0](https://github.com/devlooped/web/tree/v1.0.0) (2022-07-15)

[Full Changelog](https://github.com/devlooped/web/compare/23dbc1d83526813ee629825930bdda91276be196...v1.0.0)

:sparkles: Implemented enhancements:

- Attribute value matching does not normalize single quote values [\#30](https://github.com/devlooped/web/issues/30)
- Document all supported selectors for `text()` in readme [\#28](https://github.com/devlooped/web/issues/28)
- Add nullable annotations to public surface API [\#26](https://github.com/devlooped/web/issues/26)
- Add text\(\) pseudo-attribute selector [\#15](https://github.com/devlooped/web/issues/15)
- Add :has pseudo-class support [\#12](https://github.com/devlooped/web/issues/12)
- Add :nth-of-type pseudo class [\#11](https://github.com/devlooped/web/issues/11)
- Add :not pseudo-class [\#10](https://github.com/devlooped/web/issues/10)
- Add :first-of-type and :last-of-type pseudo classes [\#9](https://github.com/devlooped/web/issues/9)
- Add :empty pseudo-class support [\#8](https://github.com/devlooped/web/issues/8)
- Add :only-child pseudo-class selector [\#7](https://github.com/devlooped/web/issues/7)
- Add :first-child and :last-child pseudo-class selectors [\#6](https://github.com/devlooped/web/issues/6)
- Add support for :checked pseudo-class [\#5](https://github.com/devlooped/web/issues/5)
- Add minimal viable implementation of key selectors [\#1](https://github.com/devlooped/web/issues/1)

:bug: Fixed bugs:

- Child combinator selects only first child [\#36](https://github.com/devlooped/web/issues/36)
- If CSS identifier contains underscore, wrong XPath is built [\#34](https://github.com/devlooped/web/issues/34)
- If attribute value has quoted text with whitespace, fails to convert to XPath [\#22](https://github.com/devlooped/web/issues/22)
- If attribute value has quotes, XPath conversion fails [\#21](https://github.com/devlooped/web/issues/21)

:hammer: Other:

- Add support for simplified syntax for nth-child [\#38](https://github.com/devlooped/web/issues/38)
- Add support for selector groups [\#32](https://github.com/devlooped/web/issues/32)

:twisted_rightwards_arrows: Merged:

- HTML \> XML + CSS [\#48](https://github.com/devlooped/web/pull/48) (@kzu)
- Add support for simplified syntax for nth-child [\#39](https://github.com/devlooped/web/pull/39) (@kzu)
- Fix child combinator to XPath conversion [\#37](https://github.com/devlooped/web/pull/37) (@kzu)
- Properly parse underscore in CSS identifiers [\#35](https://github.com/devlooped/web/pull/35) (@kzu)
- Add support for selector groups [\#33](https://github.com/devlooped/web/pull/33) (@kzu)
- Apply single quotes normalization to attribute value matching [\#31](https://github.com/devlooped/web/pull/31) (@kzu)
- Add nullable annotations to public surface API [\#27](https://github.com/devlooped/web/pull/27) (@kzu)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
