1. Clone repo
2. `cd 1.11.3 && pnpm i && pnpm turbo build`
3. See all 5 packages are built
4. `cd ../1.12.0 && pnpm i && pnpm turbo build`
5. See only 4 packages are built: apps-b is missing
