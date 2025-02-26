# Docker compose file for running [Pi-hole6](https://pi-hole.net/) and [unbound](https://www.nlnetlabs.nl/projects/unbound/about/) in a single container

## Configuration

1. Edit the timezone
2. Edit the volumes section to fit your paths
3. Set environment variables

### Environment variables

Environment variable | Description
---------------------|----------|
$API_PASSWORD | Admin/API password for Pi-Hole
$HOSTNAME | Hostname value used by Pi-Hole
