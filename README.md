# test2

```
   {
      "Name": "Bitly Secret Key",
      "Regex": "^([0-9a-f]{40})$",
      "plural_name": false,
      "Description": null,
      "Exploit": "Use the command below to verify that the secret key is valid:\n  $ curl \"https://api-ssl.bitly.com/v3/shorten?access_token=SECRET_KEY_HERE&longUrl=https://www.google.com\"\n",
      "Rarity": 0.5,
      "URL": null,
      "Tags": [
         "Bug Bounty",
         "Credentials",
         "API Keys",
         "Bitly"
      ],
      "Examples": {
         "Valid": [
            "96f79079f1d658895d188a78f303220c6f161b05"
         ],
         "Invalid": []
      }
   },
```
