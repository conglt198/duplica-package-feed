# Duplica Package Feed Template

Bo nay dung de tao mot repo GitHub rieng lam nguon package cho Duplica.

## Cau truc

- `package-feed.json`
- `package-manifests/`
- `package-payloads/`

## Cach dung

1. Tao repo GitHub moi, vi du: `duplica-package-feed`
2. Copy toan bo file trong thu muc nay len root cua repo do
3. Lay raw URL cua:
   - `package-feed.json`
4. Dan URL nay vao:
   - `Them -> Goi noi dung -> Nguon GitHub`
5. Dau nhan bam `Lam moi feed` de thay goi moi

## Mau URL

- Feed:
  - `https://raw.githubusercontent.com/<user>/duplica-package-feed/main/package-feed.json`
- Manifest:
  - `https://raw.githubusercontent.com/<user>/duplica-package-feed/main/package-manifests/<file>.json`
- Payload:
  - `https://raw.githubusercontent.com/<user>/duplica-package-feed/main/package-payloads/<file>.json`

## Ghi chu

- `package-feed.json` ben trong se tro toi `manifest_url`
- Moi manifest se tro toi `payload_url`
- Tat ca URL nay can la URL public va doc duoc tu app
