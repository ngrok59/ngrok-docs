<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-02T10:10:59Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2wXGlwaXZkYnOxiqyFJV7XMiw0K",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wXGlwaXZkYnOxiqyFJV7XMiw0K"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2wXGkaNb465oBA4a8MeC7AhSYfR",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2wXGkaNb465oBA4a8MeC7AhSYfR"
        },
        "enabled": true
      },
      "created_at": "2025-05-02T10:10:48Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2wXGkbpE2TS8hT5CTFnDiKl66Tc",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wXGkbpE2TS8hT5CTFnDiKl66Tc"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
