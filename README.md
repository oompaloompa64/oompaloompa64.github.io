# Tesla Fleet Public Key

Static GitHub Pages host for the Home Assistant Tesla Fleet public key.

Tesla expects the public key at:

```text
https://oompaloompa64.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem
```

The matching private key is stored locally at:

```text
/Users/lobster/.openclaw/agents/main-agent/workspace/home-assistant/config/tesla_fleet.key
```

Never publish the private key.
