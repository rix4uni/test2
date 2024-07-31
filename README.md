# test2

```
   {
      "Name": "Stripe API Key",
      "Regex": "^([srp]k_live_[0-9a-zA-Z]{24})$",
      "plural_name": false,
      "Description": null,
      "Exploit": "Use the command below to verify that the API key is valid:\n  $ curl https://api.stripe.com/v1/charges -u \"API_KEY_HERE:\"\n",
      "Rarity": 1,
      "URL": null,
      "Tags": [
         "API Keys",
         "Credentials",
         "Bug Bounty",
         "Stripe"
      ],
      "Examples": {
         "Valid": [
            "sk_live_vHDDrL02ioRF5vYtyqiYBKma"
         ],
         "Invalid": []
      }
   },
```
