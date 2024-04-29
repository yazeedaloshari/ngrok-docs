<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-04-29T18:20:47Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.chgy15vcn4nabfun.local-ngrok-cname.com",
			"created_at": "2024-04-29T18:20:47Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2fmmuBzS45WYp2Nb9Tv2O6hBCSz",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2fmmuBzS45WYp2Nb9Tv2O6hBCSz"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2fmmuEK38EXqXsDjpWPhmnXyHaJ",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2fmmuEK38EXqXsDjpWPhmnXyHaJ"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.chgy15vcn4nabfun.local-ngrok-cname.com",
			"created_at": "2024-04-29T18:20:47Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2fmmuA38MCwkcKRTb0oXgObR4ro",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2fmmuA38MCwkcKRTb0oXgObR4ro"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
