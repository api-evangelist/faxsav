# FaxSav

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

FaxSav Incorporated was an Edison, New Jersey internet-fax company that sold store-and-forward and real-time fax transmission over a hybrid telephony/Internet network, letting customers bypass international long-distance rates. Products included the faxLauncher Windows desktop client, the faxMailer email-to-fax service, and Serverlink, a partner integration that let third-party fax software and application developers route documents through the FaxSav Network.

**Status: defunct.** FaxSav IPO'd in 1996, renamed itself NetMoves Corporation in February 1999, and was acquired by Mail.com, Inc. in early 2000 (SEC deregistration March 2000). Mail.com became EasyLink Services Corporation in 2001, and the business was acquired by OpenText in 2012. There is no current FaxSav product, developer program, or API.

The `faxsav.com` domain is still registered and delegated to OpenText nameservers with MX pointing at `easylink.com`, but no web server answers on port 80 or 443.

Backed by: battery-ventures

## Artifacts

- `lifecycle/faxsav-lifecycle.yml` — corporate lifecycle, SEC filing timeline, historical products, successor chain
- `security/faxsav-domain-security.yml` — live DNS/TLS/HTTP probe of `faxsav.com`
