# WatchEarn BD

Mobile-first watch-and-earn web app.

## Connected backend
- Supabase project: `fvuiisuzwezruxmlljty`
- Database tables: `watch_tasks`, `watch_task_proofs`, `watch_referrals`, `watch_withdrawals`
- Secure reward endpoint: `watch-claim-reward` Edge Function (JWT required)
- Wallet credit is performed server-side; the browser never directly increments the wallet.

## Features
- Email/password authentication
- Watch task list
- Timed completion flow
- Server-side reward claim
- Proof/history
- Wallet balance
- Referral code display
- Profile and logout

## GitHub Pages
Enable **Settings → Pages → Deploy from branch → main / root** to publish it.

## Important
Real advertising revenue, advertiser verification, and payment-provider approval are separate from this UI. Do not promise or credit rewards that are not funded/verified.