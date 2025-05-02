<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-05-02T10:10:54Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2wXGlJU251jFfjBfgzi1ty8QX9u",
          "uri": "https://api.ngrok.com/event_destinations/ed_2wXGlJU251jFfjBfgzi1ty8QX9u"
        }
      ],
      "id": "esb_2wXGlJNxepgIDqnAEm041qCnNuC",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2wXGlJNxepgIDqnAEm041qCnNuC/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2wXGlJNxepgIDqnAEm041qCnNuC"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
