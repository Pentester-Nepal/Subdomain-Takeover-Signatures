# Subdomain Takeover Signatures

_**Signatures for different platforms to verify Sub-domain Takeover vulnerabilities!**_
 
## Contribution Policy
**Make sure to append a new source, crediting the real owner, author, discoverer or resource in your Pull Requests!**

## Contribution Guidelines
You can contribute to [**signatures.json**](signatures.json) in two different ways. To add new signatures, please append them at the end of the JSON data!

### Method I: Single Signature for a Platform
*Use this method when you know of a single valid signature for subdomain takeover within a platform!*

```json
{
	"platforms": [
		{
			"platform": "...",
			"content": "..."
		},
		{
			"platform": "Platform Name, for example, GitHub Pages",
			"content": "Signature for Subdomain Takeover in GitHub Pages"
		}
	]
}
```

### Method II: Multiple Signatures for a Platform
*Use this method when you know of multiple valid signatures for subdomain takeover within a platform!*

```json
{
	"platforms": [
		{
			"platform": "...",
			"content": "..."
		},
		{
			"platform": "Platform Name, for example, GitHub Pages",
			"content": [
                "Signature 1 for Subdomain Takeover in GitHub Pages",
                "Signature 2 for Subdomain Takeover in GitHub Pages"
            ]
		}
	]
}
```

## Sources
- https://github.com/EdOverflow/can-i-take-over-xyz
