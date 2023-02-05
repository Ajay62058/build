---
title: "Certificates expiring on {{ env.CERT_EXPIRY }}"
---

The certificates on the following servers need to be updated before they expire:
{{ env.CERT_CHECKS }}

See [`doc/update-certificates.md`](https://github.com/nodejs/build/blob/HEAD/doc/update-certificates.md) for update instructions.

Generated by {{ env.ACTION_URL }}.