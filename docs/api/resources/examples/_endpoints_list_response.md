<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-02T10:10:53Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2wXGkdLf8ie5O0ZpUtYrbWBq27S",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wXGkdLf8ie5O0ZpUtYrbWBq27S"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wXGlDAnE2lB39N5G3BDZZXf96n",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-02T10:10:53Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2wXGlDAnE2lB39N5G3BDZZXf96n",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-02T10:10:51Z",
      "hostport": "0f850569f8f5.ngrok.paid:443",
      "id": "ep_2wXGl0n0HEXZTO43xO3pDLwTjZ2",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2wXGiQbPjAByskME1vKJsi4dy62",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://0f850569f8f5.ngrok.paid",
      "tunnel": {
        "id": "tn_2wXGl0n0HEXZTO43xO3pDLwTjZ2",
        "uri": "https://api.ngrok.com/tunnels/tn_2wXGl0n0HEXZTO43xO3pDLwTjZ2"
      },
      "tunnel_session": {
        "id": "ts_2wXGl1J3dmOdvTas6b98OgBY5IF",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2wXGl1J3dmOdvTas6b98OgBY5IF"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-02T10:10:51Z",
      "upstream_url": "http://localhost:80",
      "url": "https://0f850569f8f5.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-02T10:10:49Z",
      "domain": {
        "id": "rd_2wXGkdLf8ie5O0ZpUtYrbWBq27S",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wXGkdLf8ie5O0ZpUtYrbWBq27S"
      },
      "edge": {
        "id": "edgtls_2wXGkbpE2TS8hT5CTFnDiKl66Tc",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2wXGkbpE2TS8hT5CTFnDiKl66Tc"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wXGkcHsKd1lRaoDt1QK2vV8Yu0",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-02T10:10:49Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
