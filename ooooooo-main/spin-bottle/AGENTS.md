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

- Keep the uploaded game's presentation in the existing TanStack index route and focused game components; preserve the host project's runtime configuration.
- Use project-scoped Lovable Asset pointers for imported game media; archived pointers refer to another project.
- Keep this preview frontend-only; existing music search shows its unconnected state rather than introducing a service outside the requested trophy UI.
- Implement trophy and rules views in a controlled Radix dialog with shared reference styling and the heart dialog's motion, for accessible navigation and consistent animation.
- Use an anchored Radix dropdown for the game toolbar menu; it preserves outside-click dismissal, keyboard navigation and trigger focus without a dimmed dialog overlay.
- Keep settings in a controlled Radix dialog with shared shop motion; its presentation controls remain preview-only and do not introduce account or contact services.
