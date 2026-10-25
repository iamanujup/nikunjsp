# Test Series API

Live: `https://<your-project>.vercel.app/test-series/1`

## Local Run
\`\`\`bash
npm i -g vercel
vercel dev
\`\`\`

## Deploy
\`\`\`bash
vercel --prod
\`\`\`

## Naya Test Add Karna

1. `data/testSeries.json` kholo
2. `results` array ke **sabse upar** (id sabse bada) naya object add karo
3. `total` ko +1 kar do
4. Commit + push → Vercel auto-deploy
