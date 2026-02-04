# Admin-Only GitHub Workflow (Private Planning & Drafts)

You can keep planning materials, drafts, and editorial notes private while still publishing the final HTML in this public site repo. The safest approach is to use a **separate private repo** for all admin-only content.

## Recommended Setup (Private Drafts + Public Publishing)

### 1) Create a private repo for drafts
- Name example: `portfolio-blog-drafts`.
- Store:
  - Draft posts (Markdown).
  - Content calendar (this file).
  - Ideas backlog and outlines.

### 2) Use GitHub Projects (in the private repo)
- Create a Project board with columns like:
  - **Ideas** → **Drafting** → **Review** → **Scheduled** → **Published**.
- Only you (or collaborators you invite) can access it.

### 3) Publish to the public repo when ready
- When a post is finalized, copy the content into an HTML page in the public repo.
- Update `index.html` and any blog list pages to link to it.

## Optional: Single-Repo Alternative (Less Secure)
If you prefer to stay in one repo:
- Use **private branches** and keep them unmerged until publish time.
- Note: Branches in a public repo are still visible. This is **not** admin-only.

## Optional: GitHub Pages + Private Content
GitHub Pages is always public. For admin-only content:
- Keep it in the private repo.
- Publish only finalized HTML to the public site repo.

## Quick Checklist
- [ ] Create private drafts repo
- [ ] Add content calendar + template
- [ ] Use Project board for status tracking
- [ ] Publish final posts to public site repo
README.m