# Congregation Assistant

Website: https://photographicode.github.io/Congregation-Assistant_Public/

App: https://photographicode.github.io/Congregation-Assistant_Public/app/

This repository contains the built website and native application from [the source repository](https://github.com/photographicode/congregation-assistant). The R1 runtime source is `3013329e37213d06c7bd06e1ea75f2d14eee1ac9`; deployment.json and app/version.json record the same provenance. Subsequent source changes refine acceptance fixtures and release evidence without changing this runtime.

R1 restores report entry, publisher gender selection, AP review with guarded Undo/audit, the custom OCLM picker and assignment cautions, conditional auxiliary output and dismissible overlays. PDFs use embedded static Noto Sans with measured cells. Offline reports keep a tab-local draft and require manual retry. The assistant is an on-device deterministic parser; it does not send commands over the network. Confirmed records use the normal authorized backend.

Release evidence and remaining R2 work are in [POLISH-REPORT](https://github.com/photographicode/congregation-assistant/blob/main/docs/POLISH-REPORT.md). R2 order: front-door cleanup, pricing config/page, website visual lock, domain switch, translation coverage, billing. Real phones, real printers, WhatsApp delivery and Razorpay are not claimed verified.

CNAME remains absent until the owner confirms domain readiness. GitHub Pages does not apply Cloudflare-only security headers. Examples are fictional; no production records are in this static snapshot. Application code and bundled third-party fonts/packages retain their respective licenses. No end-to-end encryption claim is made.

## Verified R1 publication

Public merge 22fd986 and source merge 17128b8 are deployed. [The live browser check](https://github.com/photographicode/Congregation-Assistant_Public/actions/runs/39168535386) confirms the public root/app URLs, source runtime 3013329, a controlling service worker, zero browser errors and zero assistant/demo backend requests. [The source report](https://github.com/photographicode/congregation-assistant/blob/main/docs/POLISH-REPORT.md) records all evidence and limitations.

The source repository owner must set Settings → Pages → Source to GitHub Actions: its token received 403 and a competing legacy branch publisher remains. The public repository's branch already contains the native website/app. Full-row production export was rejected by automatic approval review; the additive AP rollout used an encrypted function-only rollback snapshot and did not rewrite report rows.
