---
sidebar_label: Zendesk
---

# Zendesk API wiki

:::note Working with the Zendesk API?
Please add your learnings, favorite links and gotchas here by [editing this page](https://github.com/nangohq/nango/tree/master/docs/docs/providers/zendesk.md).

:::

## Using Zendesk with Nango

API template name in Nango: `zendesk`  
Follow our [quickstart](../quickstart.md) to add an OAuth integration with Zendesk in 5 minutes.

Supported features in Nango:

| Feature                            | Supported                 |
| ---------------------------------- | ------------------------- |
| [Auth](/nango-auth/core-concepts)  | ✅                        |
| [Proxy](/nango-unified-apis/proxy) | ❎                        |
| Unified APIs                       | _Not included in any yet_ |



## App registration & publishing

**Rating: `Easy & fast`**
Registering an app takes only a few minutes, and you can start building immediately: [App registration docs](https://app.futuresimple.com/settings/oauth/apps)



## Useful links

- [How to register an Application](https://developer.zendesk.com/api-reference/sales-crm/authentication/introduction/#application-registration)
- [OAuth-related docs](https://developer.zendesk.com/api-reference/sales-crm/authentication/introduction/)
- [List of OAuth scopes](https://developer.zendesk.com/api-reference/sales-crm/authentication/introduction/#scopes)
- [API](https://developer.zendesk.com/api-reference/sales-crm/authentication/introduction/#scopes:~:text=Reference-,SYNC%20API,-Introduction)


## API specific gotchas
- Make sure you [read this](../nango-auth/frontend-sdk.md#connection-config) to set the correct subdomain before starting an OAuth flow for Zendesk.
