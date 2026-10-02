CRM_DEMO (static site, one file: index.html)

Deploy with the Vercel CLI:
  1. npm i -g vercel
  2. cd crm_demo
  3. vercel --prod
  4. When asked for the project name, type: crm_demo
     (Vercel names must be lowercase, so CRM_DEMO becomes crm_demo.)

Notes:
- No build step and no settings needed. Framework preset: Other.
- Each visitor gets their own private copy of the sample data. It resets when the page is reloaded.
- Sending, calls, connections and refresh are simulated. Sample data only.
