# Toolbox Clinic Admin Roster

Shift roster for Toolbox Clinic's part-time admin staff: weekly and monthly views, shift swaps, and monthly payroll totals.

Live at https://davidberlinski1-lgtm.github.io/toolbox-clinic-roster/

Staff sign in with their email. Swaps, days not worked and who has access are stored in Supabase, protected by the database's row-level security rules. The key in `config.js` is Supabase's public "anon" key, which is meant to be published.
