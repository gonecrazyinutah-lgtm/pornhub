# Red Dog Cam Models

PHP-based adult creator/model discovery frontend project, intended for deployment to a compatible PHP host such as Hostinger.

## Planned features
- Responsive model discovery grid
- Categories, tags, filtering, and model profiles
- Local flat-file caching
- Admin configuration panel
- Analytics/discovery dashboard
- Optional AI-generated profile introductions
- Sitemap generation and clean URLs
- Scheduled cache/analytics jobs

## Security
- Do not commit plaintext admin passwords, affiliate credentials, API keys, or other secrets.
- Store production secrets in environment variables or private server configuration.
- Admin authentication must use PHP `password_hash()` / `password_verify()`.
- The previously requested development password must be configured privately at deployment time rather than committed here.

## Deployment target
Hostinger-compatible PHP/Apache deployment. Runtime-writable cache/log directories should be created on the server and excluded from Git.

## Content requirements
Only lawful content involving consenting adults 18+ may be used. The deployment should include age-gating, reporting/contact information, and appropriate compliance processes for the jurisdiction and content sources involved.
