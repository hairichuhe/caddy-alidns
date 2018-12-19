# alidns
Dynamic dns plugin for Caddy serve


==============

These providers can be used to help solve the ACME DNS challenge by plugging them into Caddy 0.11.0 and newer:

```go

import _ "github.com/hairichuhe/caddy-alidns"

```

```plain

tls {
	
dns <provider>

}



Set environment ALIDNS_API_KEY with your account token