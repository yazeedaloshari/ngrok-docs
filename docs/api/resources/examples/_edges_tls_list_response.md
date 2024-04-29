<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-04-29T18:21:13Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2fmmxVOpdEG65YomOj3GQvBSbCF",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2fmmxVOpdEG65YomOj3GQvBSbCF"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2fmmwHQriY0eYBEskGo47GdSNg5",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2fmmwHQriY0eYBEskGo47GdSNg5"
				},
				"enabled": true
			},
			"created_at": "2024-04-29T18:21:03Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2fmmwHegnEr13OFRfDT1kPfWACr",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2fmmwHegnEr13OFRfDT1kPfWACr"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
