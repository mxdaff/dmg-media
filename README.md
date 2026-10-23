# dmg-media

Tempat transit sementara video DMG Office (repo publik).

Alur:
1. Video final di-commit ke branch `transit` (bukan `main`).
2. Link publik: `https://raw.githubusercontent.com/mxdaff/dmg-media/transit/<akun>/<file>.mp4` → dipakai Metricool.
3. Setelah post tayang: branch `transit` di-force-push ulang tanpa file itu (commit lama tidak lagi terjangkau, link mati).

Catatan: sesi Claude tidak diizinkan membuat Release atau menghapus branch, jadi dipakai cara force-push ini.
`main` hanya berisi README ini. Jangan taruh video di `main`.
