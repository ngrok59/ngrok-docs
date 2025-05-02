<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2wXGiYPRJ3V7GNacTpemshJ6XZ4",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2wXGiYPRJ3V7GNacTpemshJ6XZ4"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.27p1tjl8wfkeygxr6.local-ngrok-cname.com",
      "created_at": "2025-05-02T10:10:32Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wXGiZ3hDsJmdlJSTJ6BBRg5p0p",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wXGiZ3hDsJmdlJSTJ6BBRg5p0p"
    },
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
          "started_at": "2025-05-02T10:10:32Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.27p1tjl8wfkeygxr6.local-ngrok-cname.com",
      "created_at": "2025-05-02T10:10:32Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2wXGia9QNb1qE2vzhG2p5pon9w7",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2wXGia9QNb1qE2vzhG2p5pon9w7"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
