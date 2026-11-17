# Divika — Cerdas Template Kit Mirror

Static mirror of the [Holyline Cerdas template kit](https://kit.holylinedesign.com/cerdas/template-kit/home/).

The site preserves the original `/cerdas/...` path structure (HTML, CSS, JS, fonts, and images) so pages match the source markup and assets as closely as possible.

## Preview locally

Requires Node.js 18+.

```bash
npm start
```

Then open:

- Home: [http://127.0.0.1:4765/cerdas/template-kit/home/](http://127.0.0.1:4765/cerdas/template-kit/home/)
- Root redirect: [http://127.0.0.1:4765/](http://127.0.0.1:4765/)

The static server listens on **port 4765** (not 3000 / 5173 / 8080).

## Template kit pages

| Page | Local path |
|------|------------|
| Home | `/cerdas/template-kit/home/` |
| Home 2 | `/cerdas/template-kit/home-2/` |
| About | `/cerdas/template-kit/about/` |
| Blog | `/cerdas/template-kit/blog/` |
| Career | `/cerdas/template-kit/career/` |
| Contact Us | `/cerdas/template-kit/contact-us/` |
| Events | `/cerdas/template-kit/events/` |
| FAQ | `/cerdas/template-kit/faq/` |
| Instructors | `/cerdas/template-kit/instructors/` |
| Membership | `/cerdas/template-kit/membership/` |
| Program Detail | `/cerdas/template-kit/program-detail/` |
| Programs | `/cerdas/template-kit/programs/` |
| Success Stories | `/cerdas/template-kit/success-stories/` |
| 404 | `/cerdas/template-kit/404/` |

Linked blog sample posts under `/cerdas/2025/03/25/` are included as well.

## Notes

- Absolute `https://kit.holylinedesign.com` URLs were rewritten to root-relative paths for offline/local serving.
- WordPress admin/API endpoints (forms, oEmbed, feeds) are not functional in this static mirror.
- Source asset that 404s upstream (`owl.video.play.png`) is omitted.
