# Crimtan Event Snippet – Google Tag Manager Template

The official Google Tag Manager tag template for sending events to Crimtan, such as purchases,
add-to-baskets and leads, along with values from your data layer.

## Before you start

- The **Crimtan consenTag** tag (v5.0.0 or higher) must already be installed on your site.
  It's available in the Community Template Gallery as
  [Crimtan consenTag](https://github.com/Crimtan/crimtan-consentag-gtm-template).
- Your Crimtan account manager will confirm which events and parameters to send.

## Installation

1. In Google Tag Manager, go to **Templates → Tag Templates → Search Gallery**.
2. Search for **Crimtan Event Snippet** and click **Add to workspace**.

## Setup

1. Go to **Tags → New** and choose **Crimtan Event Snippet** as the tag type.
2. Choose the **Event** (for example, `purchase`).
3. Map each parameter to a GTM data layer variable (for example, `revenue` to `{{DLV - ecommerce.value}}`).
4. Set the trigger to fire when the event happens (for example, the purchase confirmation).
5. Preview to check the tag fires with the right values, then publish.

## Supported events

`view_content`, `view_item`, `add_to_cart`, `begin_checkout`, `checkout_progress`, `purchase`,
`generate_lead`, `contact`, `search`

Parameters for each event are listed in the
[Crimtan Standard Snippets](https://crimtan-docs.atlassian.net/wiki/spaces/TI/pages/35815425/Crimtan+Standard+Snippets) guide.

## Support

Contact your Crimtan account manager, or raise an issue in this repository.

## Licence

Apache 2.0. See [LICENSE](LICENSE).
