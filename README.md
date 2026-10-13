# gunnellfamilydentistry.com

Static website for Gunnell Family Dentistry (Logan, UT), served by GitHub Pages.
Built from `sites/gunnell` in Elevate-Practices/elevate-agents (`python3 build.py site`), then copied here.
Do not edit these files by hand; change the source and rebuild.

- Every old WordPress URL keeps its path. Spanish lives under `/es/`.
- `/book/` forwards to the appointment page.
- GoHighLevel chat widget (SMS) is on every page; Privacy Policy and Terms include the texting terms needed for A2P.

## Launch checklist
1. Settings > Pages: Source = Deploy from a branch, Branch = main / root. Custom domain = gunnellfamilydentistry.com (the CNAME file is already here).
2. At the domain registrar, point DNS to GitHub Pages: A records 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 and CNAME www -> elevate-practices.github.io.
3. When the certificate is ready, tick "Enforce HTTPS".
4. Check: home, a service page, /es/, /book/, the chat bubble, new-patient PDFs.
5. Submit https://gunnellfamilydentistry.com/sitemap.xml in Google Search Console.
6. Cancel the old WordPress hosting only after the new site is live and checked.
