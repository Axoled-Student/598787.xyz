# Axo Mail website / Axo Mail 官方網站

Axo Mail is an independent early-stage email tooling project.

Axo Mail 是獨立開發的電子郵件工具專案，目前既有工作為 **NTU Gmail Sync**，Claude 郵件輔助功能仍在研究與規劃中，尚未正式推出。

## Languages / 網站語言

Traditional Chinese (Taiwan) is the default, with a complete English alternative:

| Page | 繁體中文 | English |
| --- | --- | --- |
| Homepage | `/` (`index.html`) | `/en.html` |
| Privacy policy | `/privacy.html` | `/privacy-en.html` |
| Terms of service | `/terms.html` | `/terms-en.html` |

All pages expose language navigation and appropriate `hreflang` metadata.

## Development status / 開發狀態

- **Existing project**: NTU Gmail Sync, a personal Gmail synchronization utility intended to work with a user's Google OAuth authorization.
- **Planned research**: Claude-assisted email summarization, natural-language discovery, and user-reviewed reply drafts.
- **No launched Claude email integration** is claimed, and this public static website does not access Gmail data.

## Source files / 網站檔案

- `index.html`: Traditional Chinese homepage.
- `en.html`: English homepage for international visitors.
- `privacy.html` / `privacy-en.html`: the NTU Gmail Sync privacy policy.
- `terms.html` / `terms-en.html`: the NTU Gmail Sync terms.
- `site-20261008-zh-v4.css`: shared mobile-friendly styling. This is a versioned URL to avoid Safari retaining an older stylesheet.
- `CNAME`: custom domain record.
- `site.css` and `site-20261008-v3.css`: older stylesheets kept in the repository; current pages link to the versioned v4 file.

## Deployment / 部署

This is a static GitHub Pages website for https://598787.xyz. Publishing the updated pages requires merging the associated pull request into the default branch, subject to the configured Pages deployment process.

## Transparency / 專案透明性

Axo Mail is an independent project, not an assertion of incorporation or a funded startup. It is not affiliated with Google, National Taiwan University, or Anthropic. The site's published policies describe NTU Gmail Sync; they must be reviewed and revised before any future AI email processing or change to real data-handling practices.
