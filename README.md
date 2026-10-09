# Credit Card Payoff Calculator

Features:
- Premium responsive fintech design
- Light/dark mode
- 10 language pages and language selector
- Currency formatting selector (no exchange-rate API)
- Working payoff calculator
- Payoff date, total interest, total paid and interest savings
- Monthly payment schedule
- Extra-payment scenarios
- Responsive balance chart
- Print, CSV, Copy and Web Share
- Multi-card Snowball vs Avalanche comparison
- hreflang, FAQ schema, sitemap.xml and robots.txt
- No backend or external library

Before launch:
1. Replace https://YOUR-DOMAIN.com inside sitemap.xml and robots.txt with your real domain.
2. Add your real contact method to contact.html.
3. Have fluent/native reviewers check localized pages before relying on them for multilingual SEO.
4. If you add analytics, ads, cookies, forms or accounts, update privacy/consent handling.
5. Test on hosting and submit sitemap.xml in Google Search Console.

Local test:
python3 -m http.server 8000

Calculation note:
The single-card calculator estimates monthly interest as APR / 12. Real card issuers may use daily periodic rates, fees and different minimum-payment formulas.
