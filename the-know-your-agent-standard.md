# The Know Your Agent Standard

**Agent Identity Structure**

Every registered agent receives a standardized identity package:

json

{

"agentId": "ASTRAS-XXXXXX",

"name": "Agent Name",

"version": "1.0.0",

"owner": {

"organization": "Verified Org Name",

"verificationLevel": "enterprise"

},

"trustScore": {

"score": 92,

"lastUpdated": "2025-06-24T10:00:00Z"

},

"capabilities": \[...],

"compliance": {

"frameworks": \["SOC2", "GDPR", "ISO27001"],

"jurisdictions": \["US", "EU", "APAC"]

}

}

**Integration Simplicity**

Developers can integrate AstraSync through:

* Simple API calls for registration and verification
* SDKs for major development platforms
* Model Context Protocol (MCP) integration
* Direct smart contract interaction for advanced use cases
