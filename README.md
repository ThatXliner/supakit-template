# SvelteKit + Supabase

> With GitHub Actions, TypeScript, ESLint, Prettier, Vitest, and Playwright set up

## Installation (10 easy steps)

1. [Use this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) and clone that new repository locally or run [degit](https://github.com/Rich-Harris/degit):

```
degit github:ThatXliner/supabase-sveltekit
```

2. [Install the Supabase CLI](https://supabase.com/docs/guides/cli/getting-started#installing-the-supabase-cli)
3. Create your Supabase project (if you haven't already)
4. Get the project ID from the supabase.com dashboard (Settings > General > Reference ID)
5. Run `supabase init` in the directory where you copied this project template
6. Run `supabase link --project-ref <YOUR PROJECT ID HERE>` replacing `<YOUR PROJECT ID HERE>` with whatever value you found from step 4
7. Run `supabase start`
8. Run `supabase db pull`
9. Run `supabase db reset`
10. Commit everything to git and you're done!
