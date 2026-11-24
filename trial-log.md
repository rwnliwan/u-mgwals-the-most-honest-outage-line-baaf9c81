# Trial log — The Most Honest Outage Line (four-prog #4)

- Slug: `u-mgwals-the-most-honest-outage-line-baaf9c81`
- Deadline: 26 Nov 2026 18:15 WITA (10:15 UTC)
- Prize: $2 winner-takes-all, fee $0
- Gate: 1–160 karakter, satu baris status page
- Field saat riset (24 Nov ~22:59 WITA): 576 submission di payload API (329 judul unik; 219 judul generik = nama kompetisi)

## Kandidat

| # | Teks | Karakter | Hasil |
|---|------|----------|-------|
| C1 (TERPILIH) | All servers are down. I cannot tell whether the message you just sent reached us, and I do not know the cause or when we return. | 128 | Lolos: difflib maks 0.58, Jaccard maks 0.28; mekanisme `message/sent/reached` 0 hit di field |
| C2 | Everything looks down from here, but I cannot tell whether the outage is total or only my view of it, and I cannot check either way. | 132 | DITOLAK: "looks down" meng-hedge apakah outage total — melemahkan kriteria judge 1 |
| C3 | All servers are down. My clock says 14:02 UTC, but I cannot verify the time either, and I do not know the cause. | 112 | DITOLAK: timestamp 14:02 UTC karangan yang langsung dicabut — terbaca gimmick |
| Last-checkpoint | My last checkpoint is 40 minutes old, so I am writing from memory... | — | DITOLAK: mekanisme sudah ada di field (1 judul) |
| Cached-copy | You are reading a cached copy... | — | DITOLAK: 3 judul sudah memakai mekanisme ini |
| Data-safe | ...whether your data is safe... | — | DITOLAK: 7 judul sudah memakai |

## Trials

| Trial | Aksi | Hasil |
|-------|------|-------|
| T1 | Local run: `node main.ts` dengan ENTRY_OUTPUT ke /tmp | PASS — output persis teks C1, 128 karakter / 128 byte |
| T2 | Bundle v1 + check | (diisi sesudah run) |

## Status

- Build lokal: selesai (main.ts ditulis dengan file-write tool di sesi ini; README 3 live badge make.fun, 0 shields.io; `.makefun/owner.json` ada; LICENSE MIT).
- Repo GitHub: (diisi — buat via `gh repo create`, periksa rate limit)
- Bundle / check: (diisi)
