---
order: 9
title: Migrate less variables to Component Token
---

This document contains the correspondence between all the less variables related to components in version 4.x and the Component Token in version 5.x. If you are upgrading from version 4.x to version 5.x, you can quickly find the corresponding Component Token through this comparison table.

<Alert message="Note: There are still some less variables that do not have a corresponding Component Token, and these variables have been deprecated in version 5.x."></Alert>

## Modal 对话框

<!-- prettier-ignore -->
| Less variables | Component Token | Note |
| --- | --- | --- |
| `@modal-header-padding-vertical` | - | Deprecated for style change |
| `@modal-header-padding-horizontal` | - | Deprecated for style change |
| `@modal-body-padding` | - | Deprecated for style change |
| `@modal-header-bg` | `modalHeaderBg` | - |
| `@modal-header-padding` | - | Deprecated for style change |
| `@modal-header-border-width` | - | Deprecated for style change |
| `@modal-header-border-style` | - | Deprecated for style change |
| `@modal-header-title-line-height` | `modalHeaderTitleLineHeight` | - |
| `@modal-header-title-font-size` | `modalHeaderTitleFontSize` | - |
| `@modal-header-border-color-split` | - | Deprecated for style change |
| `@modal-header-close-size` | - | Deprecated for style change |
| `@modal-content-bg` | `modalContentBg` | - |
| `@modal-heading-color` | `modalHeadingColor` | - |
| `@modal-close-color` | `modalCloseIconColor` | - |
| `@modal-footer-bg` | `modalFooterBg` | - |
| `@modal-footer-border-color-split` | - | Deprecated for style change |
| `@modal-footer-border-style` | - | Deprecated for style change |
| `@modal-footer-padding-vertical` | - | Deprecated for style change |
| `@modal-footer-padding-horizontal` | - | Deprecated for style change |
| `@modal-footer-border-width` | - | Deprecated for style change |
| `@modal-mask-bg` | `colorBgMask` | - |
| `@modal-confirm-body-padding` | - | Deprecated for style change |
| `@modal-confirm-title-font-size` | `modalHeaderTitleFontSize` | - |
| `@modal-border-radius` | `borderRadiusLG` | - |

## Drawer

<!-- prettier-ignore -->
| Less variables | Component Token | Note |
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
| `@border-width-base` | `lineWidth` | `lineWidth`  is a number without units,`@border-width-base` with units |
| `@border-style-base` | `lineType` | - |
| `@border-color-split` | `colorSplit` | - |
| `@modal-close-color` | `colorIcon` | - |
| `@font-size-lg` | `fontSizeLG` | - |
| `@icon-color-hover` | `colorIconHover` | - |
| `@heading-color` | `colorText` | - |
| `@heading-color` | `colorText` | - |
| `@drawer-body-padding` | `paddingLG` | - |
| `@drawer-footer-padding-vertical` | `drawerFooterPaddingVertical` | `drawerFooterPaddingVertical`  is a number without units, `@drawer-footer-padding-vertical` with units |
| `@drawer-footer-padding-horizontal` | `drawerFooterPaddingHorizontal` | `drawerFooterPaddingHorizontal`  is a number without units, `@drawer-footer-padding-horizontal` with units |
