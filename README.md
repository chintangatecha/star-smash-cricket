# Star Smash Cricket

Ledger for the Thursday 9pm game at Star Smash, Marsden Park.

- Players open the site, pick their name, see what they owe or their credit, and mark payments after paying Rohit by PayID.
- Rohit opens the site with his admin key to approve payments and record each game. The court cost is split across who played.

Data lives in a Supabase project (`cricket`). The page only uses the public key; every change goes through database functions, and the admin ones check Rohit's key, which is not stored in this repo.
