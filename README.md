<!-- Artwork is editable SVG. See assets/EDITING.md for a short editing guide. -->
<p align="center">
  <a href="https://khalil-ay.com">Portfolio</a> &nbsp; · &nbsp;
  <a href="https://khalil-ay.com/works">My works</a> &nbsp; · &nbsp;
  <a href="https://linkedin.com/in/khalil-ay">LinkedIn</a> &nbsp; · &nbsp;
  <a href="mailto:contact@khalil-ay.com">Contact</a>
</p>

<a href="https://khalil-ay.com">
  <img src="./assets/hero.svg" width="100%" alt="Khalil Alyacoubi, full-stack software engineer. Backend systems, web interfaces, and open-source tools. Based in Palestine, available for remote roles and freelance work.">
</a>

<a href="https://khalil-ay.com/works">
  <img src="./assets/bento.svg" width="100%" alt="Hermosa: booking writes increased from 9 to 58 per second in a 1,000-VU k6 test. Flashsale: 62 to zero server errors at 300 VUs, with slower fulfillment and lower throughput. Agento API runtime, Lousin SaaS, full-stack toolkit, and 400+ Python students taught.">
</a>

<p align="center">
  <a href="https://hermosaksa.net">Hermosa</a> &nbsp; · &nbsp;
  <a href="https://github.com/KhALiLXD/Backend-Of-thrones">Flashsale source</a> &nbsp; · &nbsp;
  <a href="https://khalil-ay.com/works/18">Agento</a> &nbsp; · &nbsp;
  <a href="https://khalil-ay.com/works">All projects</a>
</p>

<details>
<summary><strong>Projects &amp; test notes</strong></summary>

- **Hermosa:** A production salon booking platform with 81 REST endpoints, 17 tables, and four user roles. Booking writes increased from 9 to 58 per second in a 1,000-VU k6 test; no double-bookings or timeouts were observed in that test.
- **Flash-sale system:** A comparison of synchronous and queue-based order paths. At the same 300-VU peak load, server errors fell from 62 to zero. The queue-based run recorded zero failed requests out of 108,844 and no stranded stock. The tradeoff: p95 fulfillment increased from 5.0 s to 8.1 s, while throughput decreased from 72.9 to 32.5 requests/s.
- **Agento:** An open-source runtime on npm that brings conversational access to REST APIs. Includes approvals bound to the exact write call, replay prevention, timeouts, size limits, circuit breakers, and safe retries across five model providers.
- **Lousin:** A co-founded, multi-tenant Discord-bot SaaS that consolidated more than ten dashboards and CLIs into one abstraction layer.
- **Teaching:** Advanced Python instruction for 400+ students at the Islamic University of Gaza.

Flash-sale figures come from a closed-model k6 run against a **mock payment gateway**. These are results from specific tests, not production guarantees. Methodology, known defects, and threats to validity are documented in the flash-sale repository’s `ANALYSIS_REPORT.md`.

</details>


