# NRT-KQL

To create NRT rules, we needed to be certain about the KQL syntax that can and cannot be used. This led us to create our own documentation by following five simple steps:
- Take a deep breath.Browse through Microsoft’s KQL documentation.
- Evaluate NRT convertibility in Defender.
- Evaluate NRT convertibility in Sentinel.
- Repeat.
- After many deep breaths, we ended up with more than 500 KQL syntax elements evaluated and sorted these into four categories: tables, functions, operators, and statements.

For every category, we created a JSON file and populated it with our findings. The JSON follows the format:

```json
“m365”: {
  “Accepted”: [],
  “Prohibited”: []
},
“Sentinel”: {
  “Accepted”: [],
  “Prohibited”: []
}
```
