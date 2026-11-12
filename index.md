# Reseller Hub Privacy Policy

**Effective date:** November 11, 2026  
**Last updated:** November 11, 2026

## 1. Introduction

Reseller Hub ("the Application") is a privately developed, self-hosted application intended to help its operator manage eBay selling activities, including inventory, listings, orders, shipping, and related workflows.

Reseller Hub is presently developed for the operator's own selling activities. It is not offered as a public service or a commercial multi-user software platform.

This policy describes the information the Application may access, how it is used and protected, and how privacy-related requests are handled.

Reseller Hub is independent of eBay Inc. and is not endorsed or sponsored by eBay.

## 2. Information accessed

With authorization through eBay's official OAuth process, Reseller Hub may access information made available by the eBay APIs for which permission has been granted. Depending on the enabled features, that can include:

- **Seller account information:** Account identifiers and information required to maintain an authorized connection.
- **Listings and inventory:** Item IDs, titles, descriptions, prices, quantities, listing status, and listing history.
- **Orders and transactions:** Order identifiers, purchased items, quantities, transaction statuses, and fulfillment details.
- **Shipping:** Carrier names, tracking numbers, shipping addresses, and delivery statuses.
- **Buyer information:** Buyer identifiers, names, addresses, and contact details when made available by eBay and needed for permitted seller activities.
- **Post-sale activities:** Returns, cancellations, inquiries, refunds, and related statuses.

Reseller Hub does not request or collect the seller's eBay password. Access is limited by the scopes authorized through eBay.

## 3. Uses of information

Information obtained through eBay is used to support legitimate seller operations, such as:

- Reviewing inventory and listing performance.
- Monitoring sales, orders, and fulfillment.
- Tracking shipments and delivery exceptions.
- Identifying relationships between ended and relisted listings.
- Reviewing returns, cancellations, and buyer inquiries.
- Producing operational summaries and notifications.

Reseller Hub does not sell or rent buyer or seller personal information, use it for unrelated advertising, or provide it to data brokers. eBay-derived personal information is not used to train artificial intelligence or machine-learning models.

## 4. Authentication and access tokens

Reseller Hub uses eBay OAuth to obtain access only after the seller authorizes the requested permissions. The seller authenticates with eBay, not with Reseller Hub.

During the temporary **Phase 0 API-validation process**, OAuth client credentials and refresh tokens are stored locally on the operator's Windows computer using Windows Data Protection API (DPAPI) encryption. Access tokens are handled in memory.

The planned permanent Application will be self-hosted on infrastructure controlled by the operator and is designed to manage OAuth access independently, with encrypted credential storage. That permanent deployment is under development.

The seller may revoke an authorization using the applicable eBay account permissions and application-access controls. Revoking access prevents further authorized API retrieval but does not automatically delete information previously stored for permitted purposes.

## 5. Storage and security

Reseller Hub is designed for privately controlled, self-hosted operation rather than as a public cloud software service.

Security safeguards for deployed components, as applicable, include:

- Access restrictions for the Application and supporting infrastructure.
- Protection of OAuth credentials and tokens.
- HTTPS for communications with eBay and other external APIs.
- Data minimization in logs, reports, and notifications.
- Retention of personal information only when needed for permitted seller activities or applicable obligations.

The temporary Phase 0 probe processes API responses in memory and generates sanitized reports consisting of field structure, counts, selected status values, and summary statistics. Those reports are designed to exclude buyer names, addresses, emails, tracking numbers, item titles, and transaction identifiers.

No technical system can guarantee absolute security. Safeguards may evolve as the Application is developed.

## 6. External services

eBay is the primary external service used for seller authorization and marketplace data access.

Additional integrations may be added when implemented and enabled, including:

- Shipping and tracking providers such as EasyPost.
- Notification providers such as Pushover or Gotify.

These integrations are **planned or optional**, not a representation that they are currently deployed. When activated, information will be shared only as reasonably necessary to provide the selected feature, subject to the relevant provider's own privacy practices.

Reseller Hub does not disclose buyer information to advertising networks or data brokers.

## 7. Retention and deletion

Information is retained only as reasonably necessary for authorized selling operations, applicable legal or recordkeeping requirements, and eBay's developer requirements. Retention periods may differ by data category.

Information that is no longer required will be deleted or de-identified as appropriate. Valid requests concerning personal information will be evaluated and handled in accordance with applicable law and eBay's requirements.

At the end of Phase 0 validation, the operator can delete locally stored OAuth credentials, tokens, and generated reports and revoke the temporary eBay authorization.

## 8. Buyer privacy

Buyer personal information accessed through eBay is used only for permitted seller purposes, such as fulfillment, shipping, transaction support, and post-sale service.

It is not used for unsolicited marketing, publicly shared buyer profiles, or unrelated commercial purposes.

Questions or requests about personal information handled by Reseller Hub can be sent to the contact email below. For information maintained by eBay itself, individuals should consult eBay's own privacy notice and privacy controls.

## 9. Cookies and website analytics

Reseller Hub is not currently operated as a public-facing application and does not employ third-party advertising trackers.

This Privacy Policy may be published through GitHub Pages. GitHub may process technical information about visitors to hosted pages under GitHub's own privacy practices. The policy website does not intentionally deploy application-specific advertising cookies or analytics scripts.

If these practices materially change, this policy will be updated.

## 10. Privacy requests

Individuals may have privacy rights under applicable law, including rights to request information, correction, or deletion of personal information.

Please send privacy inquiries and requests to **ebay@georgesonfamily.com**. Requests will be reviewed and handled as required by applicable law, eBay policies, and legitimate recordkeeping obligations.

## 11. Changes to this policy

This policy may change as the Application develops, integrations are enabled, or legal and platform requirements change. An updated version will be published at this URL with a revised "Last updated" date.

## 12. Contact

**Application:** Reseller Hub  
**Operator:** Privately operated, United States  
**Privacy contact:** [ebay@georgesonfamily.com](mailto:ebay@georgesonfamily.com)

---

*eBay and related marks are trademarks of their respective owners. Reseller Hub is an independent application.*
