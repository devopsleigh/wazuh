# Wazuh

## Disable SSL

We'll be using a proxy to access Wazuh, so we need to disable SSL that is configured during the container setup.

Edit `config/wazuh_dashboard/opensearch_dashboards.yml` and comment out `server.ssl.enabled: true`
