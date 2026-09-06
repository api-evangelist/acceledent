# AcceleDent

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AcceleDent was the flagship product of OrthoAccel Technologies, Inc., a privately held medical-device company founded in 2007 and headquartered in Bellaire, Texas, outside Houston. AcceleDent is an FDA-cleared Class II device built around the company's patented SoftPulse Technology: a hands-free mouthpiece and activator that a patient bit down on for about twenty minutes a day, delivering gentle micropulses intended to speed bone remodeling during orthodontic treatment and reduce the discomfort of braces and clear aligners. The line ran through three generations — the original AcceleDent, AcceleDent Aura in 2013, and AcceleDent Optima, cleared by the FDA in 2017 — sold to orthodontists and dentists rather than direct to consumers, with an e-commerce ordering site at shop.acceledent.com for practices. The company raised roughly $63.1M across sixteen rounds, the last a Series C in January 2017, and a later debt-and-equity financing led by S3 Ventures. It was a physical medical-device business, not a software business: OrthoAccel never operated a developer program, never published an API, SDK, webhook surface or machine-readable specification of any kind, and shipped no client libraries to any package registry. OrthoAccel is now reported defunct — orthoaccel.com no longer resolves, and acceledent.com was re-registered on 2022-08-30 and today sits on Afternic name servers as a GoDaddy aftermarket "for sale" listing whose parking system answers HTTP 200 with an identical 114-byte HTML stub on every path, including every /.well-known/ and spec path. This profile is retained as a historical record; there is no API surface to enrich.

## Coverage

**No API surface.** This is a historical record, not a thin profile. OrthoAccel Technologies
built AcceleDent as a physical FDA-cleared Class II orthodontic device and never operated a
developer program. `orthoaccel.com` no longer resolves; `acceledent.com` was re-registered on
2022-08-30 and now serves a GoDaddy aftermarket "for sale" lander that answers HTTP 200 with an
identical 114-byte HTML stub on every path — including `/openapi.json` and every
`/.well-known/` path — so none of those 200s is a document.

The full negative probe record, with every URL and status code, is in
[`well-known/acceledent-well-known.yml`](well-known/acceledent-well-known.yml). No `WellKnown`,
`SecurityTxt`, `AgentCard`, `LLMsTxt` or `OpenAPI` pointer is emitted from it, and none should
be added in a later round without a 200 carrying a real document.

Secondary-market listing (the harvest source, not a company website):
<https://forgeglobal.com/acceledent_stock/>
