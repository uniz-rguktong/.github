<p align="center">
  <img width="1680" height="1050" alt="UniZ" src="https://github.com/user-attachments/assets/82b4ba14-c1a2-4bf9-96b1-83b46ba38544" />
</p>

<p align="center">
  <a href="https://uniz.rguktong.in"><b>UniZ</b></a> — open campus platform for RGUKT Ongole
</p>

<p align="center">
  Student &amp; admin portals · academics · outpass · grades · notifications · Android TWA<br/>
  TypeScript monorepo on K3s · PostgreSQL · Prisma · Redis · GitHub Actions
</p>

### Source of truth

| Repository | Purpose |
|---|---|
| **[uniz-master](https://github.com/uniz-rguktong/uniz-master)** | Entire product: APIs, portal, landing, docs, infra, **and Android app** |
| **[uniz-hall-ticket](https://github.com/uniz-rguktong/uniz-hall-ticket)** | Standalone hall-ticket utility |
| **[.github](https://github.com/uniz-rguktong/.github)** | Organization profile & community defaults |

The Android client is **not** a separate app repo. It lives in `uniz-master` as a Trusted Web Activity (`apps/uniz-android-twa`). Build with `npm run android:apk`; students download from [uniz.rguktong.in/download/uniz.apk](https://uniz.rguktong.in/download/uniz.apk).

### Start here

1. Clone [uniz-master](https://github.com/uniz-rguktong/uniz-master)
2. Read [STRUCTURE.md](https://github.com/uniz-rguktong/uniz-master/blob/main/STRUCTURE.md) and [docs/org](https://github.com/uniz-rguktong/uniz-master/blob/main/docs/org/README.md)
3. Local setup: [CONTRIBUTING.md](https://github.com/uniz-rguktong/uniz-master/blob/main/CONTRIBUTING.md)

### Links

- Portal: [uniz.rguktong.in](https://uniz.rguktong.in)
- Docs: [api-uniz.rguktong.in/docs](https://api-uniz.rguktong.in/docs)
- Security: report privately per [SECURITY.md](https://github.com/uniz-rguktong/uniz-master/blob/main/SECURITY.md)
