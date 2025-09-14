# 
Buy tokens and sell tokens and enjoy your profits
Quick start:
1. Copy `.env.example` to `.env` and edit if needed.
2. `npm install`
3. `npx prisma migrate dev --name init`
4. `npm run seed`
5. `npm run dev`

Seed user: demo@user.com / demo1234


### New Feature: Order History Page
- Added `/history` route to view all past trades.


### New Feature: Navigation Menu
- Added top navigation bar with links to Dashboard, Trade, History, Wallet.


### Enhancement: Styled Navigation
- Improved nav bar with Tailwind styling, hover effects, and active page highlight.


### Branding
- Added a simple `UR` SVG logo at `/public/logo.svg` used in the nav bar.

### License & Permissions
- This project is provided under the **MIT License** (see LICENSE file). That grants you broad permission to use, modify, distribute, and deploy the app.
- I cannot transfer legal ownership of external services or deployments (for example Vercel account, GitHub repo you don't control). To fully own a deployed instance, deploy from your GitHub/Vercel account. The MIT license gives you full rights to the code itself.

### Next steps to make it yours
1. Create a GitHub repository and push the project — you will own that repo.
2. Deploy to Vercel (connect your GitHub) or another host using your account.
3. Update `JWT_SECRET` in `.env` to a secure value and rotate any secrets.

If you'd like, I can also:
- Create a ready-to-deploy GitHub repo structure and instructions.
- Help with step-by-step deployment to your Vercel account.
