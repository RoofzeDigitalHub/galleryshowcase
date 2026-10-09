<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Shared workforce navigation, enquiry forms and page primitives live in one browser-safe site module so contact actions and brand presentation stay consistent across pages.
- Service and job enquiries open WhatsApp with user-entered details instead of claiming website-side storage or confirmed vacancies.
- Each content page uses a distinct TanStack file route and its own social metadata so navigation and page previews remain unambiguous.
- Extended Home sections and workforce enquiry categories live in a separate browser-safe module shared with the enquiry form; below-fold photos use compressed WebP and lazy loading to limit page weight.
