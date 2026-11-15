# AMC Receivables

Receivables manager for lift AMC contracts: clients, payment plans, monthly budgets, invoices, payments and reports, with team accounts.

- Sign in with Google, or with an email and password
- New accounts wait for admin approval, then get **Review only** or **Edit** access
- After approval, each person adds their name and profile photo
- Each client has a payment plan (monthly, quarterly, every 4 or 6 months, annually, or specific months)
- Monthly budgets come from those plans and download as Excel or PDF
- Every record has an edit history showing who changed what, and when
- Changes appear for everyone live

Hosted on GitHub Pages, with Supabase for sign-in, data, edit history and photos. Client data is stored only in Supabase, never in this repository.
