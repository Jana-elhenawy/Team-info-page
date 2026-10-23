# Team Members Page

A responsive static website for the **Advanced Software Engineering** course project. It is deployed with GitHub Pages through GitHub Actions.

## Files

- `index.html` — website content and team-member cards.
- `style.css` — responsive styling.
- `.github/workflows/deploy.yml` — deploys the site when changes are pushed to `main`.

## Add your team-member details

1. Clone the repository.
2. Create a new branch, for example `add-your-name`.
3. Open `index.html` and duplicate the existing `<article class="member-card">...</article>` block.
4. Replace the initials, name, student ID, department, and course with your details.
5. Commit and push your branch, then open a pull request targeting `main`.
6. After the pull request is reviewed and merged, GitHub Actions will deploy the updated page.

Keep each new card inside the `<div class="team-grid">` element. Do not replace the whole page or edit another member's card unnecessarily.

## Enable GitHub Pages

In the GitHub repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. Then open the **Actions** tab to monitor deployment. After a successful run, the published URL appears in the workflow run and in Settings → Pages.

## Suggested contribution workflow

Each teammate should use their own GitHub account, create a separate branch, make a focused change, and submit a pull request. This gives the team a clear contribution history.
