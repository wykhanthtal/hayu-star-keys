# hayu-star-keys

Key list for the HAYU star app. The app reads `keys.json` from this public repo.

Each entry in `keys` is an object:
- `hash`: SHA-256 hash of the key (plain keys are never stored here)
- `expire`: expiry date, e.g. `2027-10-30` (or `never`)
- `note`: who the key was given to

Example:
```json
{
  "keys": [
    {"hash": "<sha256-of-key>", "expire": "2027-10-30", "note": "customer name"}
  ]
}
```
