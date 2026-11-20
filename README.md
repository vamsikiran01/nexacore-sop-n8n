# Nexacore SOP n8n Service

Self-hosted n8n instance configured for Render.com Free Tier with Supabase PostgreSQL backend.

## Deployment to Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

1. Click the **Deploy to Render** button above or link your GitHub repo in Render Blueprints.
2. Provide your Supabase PostgreSQL credentials when prompted:
   - `DB_POSTGRESDB_HOST`: Supabase session pooler host (e.g. `aws-0-[region].pooler.supabase.com`)
   - `DB_POSTGRESDB_USER`: Supabase database username (e.g. `postgres.[project-ref]`)
   - `DB_POSTGRESDB_PASSWORD`: Supabase database password
3. Click **Apply** to deploy the service.
