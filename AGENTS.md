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

- Organizational records are owner-scoped in Cloud with composite company foreign keys, so companies cannot cross-link private data.
- Public content routes display a labeled sample until sign-in; authenticated server functions and storage policies enforce all real-data access.
- Job hierarchy uses React Flow positions and a cycle-validated superior foreign key; independent visual connections use an owner/company-scoped table so drawing lines cannot change reporting relationships.
- Render only manual org-chart edges, with persisted endpoint sides and loose four-side handles, so supervisor edits never draw or remove arrows.
- Export layouts are browser-local and user-keyed, shared by the editor and all current PDF/CSV exports, so sample preferences and account preferences remain separate.
- Load PDF.js and its worker dynamically after hydration to render PDF previews reliably across browsers without server evaluation of browser-only code.
- Job PDFs are generated from record data in the browser with paginated text, so exports include every field without screenshot clipping; attachment blobs are prepared before download clicks for mobile reliability.
- Gemini summaries use request-local AI SDK gateway helpers in server-only modules, so secrets never enter the browser.
- People records use authenticated server functions and company/owner composite foreign keys; private document uploads are owner-folder scoped with format restrictions.
- Employee step transitions share Zod validation with server saves; dependents can persist with pending documents, and their status is derived from active state and age-dependent required documents.
- News records are owner-scoped and use signed private image URLs; the home feed falls back to a labeled illustrative article without writing sample records.
- Keep employee read compatibility for missing newly introduced JSON fields, but require admission dates on every save so existing records can be corrected without invented dates.
- The access page renders without the workspace shell; account controls share the workspace session and never store privileges in user metadata.

- Document assignments synchronize through database triggers for types, employees and jobs; unique person/type rows prevent overlapping assignments from duplicating obligations.
- Document actions run in an authenticated transactional database function and every change appends an immutable snapshot history, so bulk validation is atomic and renewals preserve past dates and files.
- Vacation status (Confirmada/Aviso) is derived from the approved state, dates and a finished flag at read time, so no scheduled job is needed to move statuses.
- Lunch entries share an owner/company-scoped ledger with private per-entry capture photos; facial entries have a daily unique key while manual and visitor entries allow additional and retroactive meals. Legacy entries retain their original history without invented photos.
- Lunch validation compares the stored employee face photo with a totem camera capture via Gemini server-side; all entry points share Brasília date and photo validation rules.
