# DDNS-Cloudflare
This is a simple DDNS script to update the IP on Cloudflare

To obtain the ID for the record, please use this API call:

curl --request GET   --url https://api.cloudflare.com/client/v4/zones/ZONEID/dns_records   --header 'Content-Type: application/json'   --header 'Authorization: Bearer '   --header 'X-Auth-Email: @gmail.com' | jq
