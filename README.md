# Divine Care Pharmacy

Appointment booking and low-stock ordering for Divine Care Pharmacy, Pesalai.

## Run locally

From a terminal, run:

```sh
git clone https://github.com/HamnaFazil/divine-care-pharmacy.git
cd divine-care-pharmacy
git switch develop
npm install
npm run dev
```

Before starting the app, copy `.env.example` to `.env.local` and add the Supabase
values shared by the team through the password manager. Never commit `.env.local`.
The app is available at [http://localhost:3000](http://localhost:3000).

Other useful commands:

```sh
npm run lint
npm run typecheck
npm run build
npm run format
```

## Branch rules

Start feature branches from `develop` and use pull requests. The intended rules
are one approval and passing CI before merge, with direct pushes, force pushes,
and deletion blocked. See the [team branch rules](./docs/team-rules.md).

## Folder ownership

The setup brief identifies Suwetha with the public home page and Thamilini with
database migrations. The remaining folder-to-owner assignments were not
included; confirm them against the team's ownership guide before assigning work.

- `src/app/(public)/`: Suwetha (public pages)
- `supabase/`: Thamilini (database migrations)
- Other `src/` folders: follow the team ownership guide
