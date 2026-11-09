# ds3-unseen-witness

Author-owned OIDC identity witness for the r51 DS3 confirmation-style capture. The workflows copy one source workflow from each of eight previously unseen public repositories; job/needs/matrix/uses structure is preserved, original run steps are adapted to no-ops, and every adaptation is recorded in `.github/witness/adaptation-manifest.json`. Execution is a controlled re-execution under this author account, not the upstream project's CI.
