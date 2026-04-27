# PrimePulse OPS Token Preview Scan

This version prioritizes CTR:
- OG/Twitter preview image = token image from DexScreener (`pair.info.imageUrl`)
- Fallback image = PrimePulse OPS logo
- Twitter card = summary_large_image
- Page hero shows token image + PrimePulse branding
- Server-side token-specific metadata remains active
- Accepts DexScreener URL, pair address, contract, encoded/nested URLs

Use:
https://YOUR-VERCEL-DOMAIN/scan/solana/PAIR_ADDRESS
