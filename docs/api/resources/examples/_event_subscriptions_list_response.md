<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-04-29T18:21:09Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2fmmx1lEbLoNZbFKX1z1iY2rq7B",
					"uri": "https://api.ngrok.com/event_destinations/ed_2fmmx1lEbLoNZbFKX1z1iY2rq7B"
				}
			],
			"id": "esb_2fmmx2ht0fAr8GN6au4y9hoc1PR",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2fmmx2ht0fAr8GN6au4y9hoc1PR/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2fmmx2ht0fAr8GN6au4y9hoc1PR"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
