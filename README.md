# job-scrapers

## Notes:

- Multithreading for increased speed
  - Technically for such problems, multi-threading would serve us well since its an io-bound (network) task.
  - However, we will not utilise it here so as to avoid the risk of being banned e.g. making too many requests within a short period of time
- Potential for monetisation
  1. LinkedIn does not have official APIs and API-key mechanisms (temporary authentication) that supports this
  2. Due to security reason(s) and concern(s), it is not preferred for users to submit their credentials to their own LinkedIn accounts
  3. Reusing our same/ few different accounts for scraping jobs submitted by many users will also likely get the account(s) banned; and is therefore not scalable.
