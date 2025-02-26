# Docker compose file for running [Pi-hole6](https://pi-hole.net/) and [unbound](https://www.nlnetlabs.nl/projects/unbound/about/) in a single container

Pi-Hole responds on port 80 and 443 (with self signed cert). Unbound mapped to port 5353.

## Configuration

1. Edit the timezone
2. Edit the volumes section to fit your paths (for both Pi-hole and Unbound)
3. Set environment variables
4. Deploy

### Environment variables

Environment variable | Description
---------------------|----------|
$API_PASSWORD | Admin/API password for Pi-Hole (can be hashed or clear text
$HOSTNAME | Hostname value used by Pi-Hole
$TX |[ timezone]
