# Congregation Assistant

Website: https://photographicode.github.io/Congregation-Assistant_Public/

App: https://photographicode.github.io/Congregation-Assistant_Public/app/

This repository contains the built website and native application from [the source repository](https://github.com/photographicode/congregation-assistant). The R1 runtime source is `3013329e37213d06c7bd06e1ea75f2d14eee1ac9`; deployment.json and app/version.json record the same provenance. Subsequent source changes refine acceptance fixtures and release evidence without changing this runtime.

R1 restores report entry, publisher gender selection, AP review with guarded Undo/audit, the custom OCLM picker and assignment cautions, conditional auxiliary output and dismissible overlays. PDFs use embedded static Noto Sans with measured cells. Offline reports keep a tab-local draft and require manual retry. The assistant is an on-device deterministic parser; it does not send commands over the network. Confirmed records use the normal authorized backend.

Release evidence and remaining R2 work are in [POLISH-REPORT](https://github.com/photographicode/congregation-assistant/blob/main/docs/POLISH-REPORT.md). R2 order: front-door cleanup, pricing config/page, website visual lock, domain switch, translation coverage, billing. Real phones, real printers, WhatsApp delivery and Razorpay are not claimed verified.

CNAME remains absent until the owner confirms domain readiness. GitHub Pages does not apply Cloudflare-only security headers. Examples are fictional; no production records are in this static snapshot. Application code and bundled third-party fonts/packages retain their respective licenses. No end-to-end encryption claim is made.
