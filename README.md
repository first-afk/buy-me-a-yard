# Buy Me a Yard 
A localized support platform enabling fans to fund African and Nigerian creators through culturally relevant, virtual "yards" of materials (Ankara, lace, aso-oke). Designed to bypass geoblocking and payout friction, this platform integrates local payment rails alongside international gateways to ensure seamless monetization for creators.

## Features (MVP Scope)
  - For Creators: 
     - Custom Yard Menu: Configure accepted materials (e.g., Ankara, Adire) and set pricing.
     - Frictionless Payouts: Direct local bank withdrawals via integrated payment gateways (Paystack/Flutterwave).
     - Supporter Wall: Public or anonymous ledger of gifted yards and thank-you notes.Dashboard: Track earnings, payout history, and supporter messages.
  - For Supporters:
    - One-Off Gifting: "Buy a yard" using local (NGN) or international payment methods.
    - Cross-Border Support: Seamless currency conversion handling to prevent geoblocking.
    - Personalized Messaging: Attach custom notes to gifts.

## Tech Stack
Frontend: Next.js, React, TypeScript
Styling: Tailwind CSS
Backend & Database: Supabase (PostgreSQL) with Row-Level Security (RLS)
Payments: Paystack & Flutterwave APIs
Testing: Jest
Deployment: Vercel

## Prerequisites
Ensure you have the following installed before running the project: Node.js (v18.x or later), npm, yarn, or pnpm


## Getting Started
1. Clone the repository
   ```
   git clone https://github.com/your-org/buy-me-a-yard.git
   cd buy-me-a-yard

2. Install dependencies
```
   npm install or yarn install / pnpm install
```
3. Set up environment variables
Create a .env.local file in the root directory and add the following supabase keys:

```
  NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
  NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
  SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key
```

4. Run the local development server
```
   npm run dev
```
Navigate to http://localhost:3000 to view the application.

## Testing
This project uses Jest to test components and utility functions. Run the test suite
```
  npm run test
```

## Contributing
We welcome contributions! Please review our Contributing Guidelines before submitting a pull request to ensure smooth collaboration.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
