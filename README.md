# Congregation Assistant — public V3 checkpoint

Website: https://photographicode.github.io/Congregation-Assistant_Public/

App demo: https://photographicode.github.io/Congregation-Assistant_Public/app/?demo=admin

This repository publishes a built snapshot from [the source repository](https://github.com/photographicode/congregation-assistant), source commit `674e3f1d055752434e38229e564b285fcba00e36`, merged through [PR #41](https://github.com/photographicode/congregation-assistant/pull/41). Source/version metadata is also in deployment.json and app/version.json. The site and app ship in one Pages artifact; the existing root publishing path also remains usable.

This is a review checkpoint, not full V3 completion. [The cutover report](https://github.com/photographicode/congregation-assistant/blob/main/docs/CUTOVER-REPORT.md) lists remaining work and tests. Official-source import returned HTTP 400, so Add parts remains the fallback. One combined production meeting-workflow migration was rejected by automatic review and remains unapplied. SFTS and confirmed-report endpoints were applied with authenticated-only privileges.

The supplied form reference files are excluded. Layouts are independently drawn. Examples are fictional. Application code is All rights reserved; bundled third-party packages and fonts retain their respective licenses. No end-to-end encryption claim is made. The assistant is a deterministic on-device parser; confirmed records use the normal backend.

CNAME is intentionally absent until the owner confirms DNS. GitHub Pages does not supply the Cloudflare security headers. Real login requires provider redirect configuration for the Pages app URL.
