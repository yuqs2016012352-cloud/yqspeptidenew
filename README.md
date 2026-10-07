# yqs_peptide_info

ImmunePeptide Atlas, a small peptide information database ready for Netlify and PostgreSQL.

Deploy this repository as a Netlify site. The frontend calls `/api/peptides`, routed to the Netlify Function in `netlify/functions/peptides.mjs`.

After enabling Netlify Database, apply the migration in `netlify/database/migrations/`.
