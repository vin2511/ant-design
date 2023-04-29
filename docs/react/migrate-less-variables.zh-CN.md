---
order: 9
title: less 变量迁移 Component Token
---

本文档包含了所有 4.x 版本中组件相关的 less 变量与 5.x 版本的 Component Token 的对照关系。如果你是从 4.x 版本升级到 5.x 版本，可以通过这份对照表快速找到对应的 Component Token。

<Alert message="注意：仍有部分变量没有对应的 Component Token，这些变量在 5.x 版本中已被废弃。"></Alert>

## Modal 对话框

<!-- prettier-ignore -->
| less 变量 | Component Token | 备注 |
| --- | --- | --- |
| `@modal-header-padding-vertical` | - | 由于样式变化已废弃 |
| `@modal-header-padding-horizontal` | - | 由于样式变化已废弃 |
| `@modal-body-padding` | - | 由于样式变化已废弃 |
| `@modal-header-bg` | `modalHeaderBg` | - |
| `@modal-header-padding` | - | 由于样式变化已废弃 |
| `@modal-header-border-width` | - | 由于样式变化已废弃 |
| `@modal-header-border-style` | - | 由于样式变化已废弃 |
| `@modal-header-title-line-height` | `modalHeaderTitleLineHeight` | - |
| `@modal-header-title-font-size` | `modalHeaderTitleFontSize` | - |
| `@modal-header-border-color-split` | - | 由于样式变化已废弃 |
| `@modal-header-close-size` | - | 由于样式变化已废弃 |
| `@modal-content-bg` | `modalContentBg` | - |
| `@modal-heading-color` | `modalHeadingColor` | - |
| `@modal-close-color` | `modalCloseIconColor` | - |
| `@modal-footer-bg` | `modalFooterBg` | - |
| `@modal-footer-border-color-split` | - | 由于样式变化已废弃 |
| `@modal-footer-border-style` | - | 由于样式变化已废弃 |
| `@modal-footer-padding-vertical` | - | 由于样式变化已废弃 |
| `@modal-footer-padding-horizontal` | - | 由于样式变化已废弃 |
| `@modal-footer-border-width` | - | 由于样式变化已废弃 |
| `@modal-mask-bg` | `colorBgMask` | - |
| `@modal-confirm-body-padding` | - | 由于样式变化已废弃 |
| `@modal-confirm-title-font-size` | `modalHeaderTitleFontSize` | - |
| `@modal-border-radius` | `borderRadiusLG` | - |

## Drawer 抽屉

<!-- prettier-ignore -->
| less 变量 | Component Token | 备注 |
| --- | --- | --- |
| `@zindex-modal` | `zIndexPopup` | - |
| `@modal-mask-bg` | `colorBgMask` | - |
| `@animation-duration-slow` | `motionDurationSlow` | - |
| `@shadow-1-right` | `boxShadowDrawerLeft` | - |
| `@shadow-1-left` | `boxShadowDrawerRight` | - |
| `@shadow-1-down` | `boxShadowDrawerUp` | - |
| `@shadow-1-up` | `boxShadowDrawerDown` | - |
| `@drawer-bg` | `colorBgElevated` | - |
| `@drawer-header-padding` | `padding`、`paddingLG` | `${padding}px ${paddingLG}px` |
| `@drawer-title-font-size` | `fontSizeLG` | - |
| `@drawer-title-line-height` | `lineHeightLG` | - |
| `@border-width-base` | `lineWidth` | `lineWidth` 为数字，不带单位，`@border-width-base` 带单位 |
| `@border-style-base` | `lineType` | - |
| `@border-color-split` | `colorSplit` | - |
| `@modal-close-color` | `colorIcon` | - |
| `@font-size-lg` | `fontSizeLG` | - |
| `@icon-color-hover` | `colorIconHover` | - |
| `@heading-color` | `colorText` | - |
| `@heading-color` | `colorText` | - |
| `@drawer-body-padding` | `paddingLG` | - |
| `@drawer-footer-padding-vertical` | `drawerFooterPaddingVertical` | `drawerFooterPaddingVertical` 为数字，不带单位，`@drawer-footer-padding-vertical` 带单位 |
| `@drawer-footer-padding-horizontal` | `drawerFooterPaddingHorizontal` | `drawerFooterPaddingHorizontal` 为数字，不带单位，`@drawer-footer-padding-horizontal` 带单位 |
