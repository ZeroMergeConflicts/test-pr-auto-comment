# 🚀 Pull Request #{number}

## 📌 Summary

**Title:** {title}  
**Author:** @{author}  
**Repository:** {owner}/{repo}  

**Branch:** `{branch}` → `{base}`  
**Created:** {created_at}  

---

## 📊 Change Metrics

- **Files changed:** {changed_files}
- **Additions:** +{additions}
- **Deletions:** −{deletions}
- **Size classification:** **{size}**

---

{#if draft}
## ⚠️ Draft Status

This pull request is currently marked as **draft**.  
It may be under active development and not ready for full review.
{/if}

---

{#if labels}
## 🏷️ Labels

**List:** {labels:comma}  

**Mentions:** {labels:mentions}

**Lines:**
{labels:lines}
{/if}

---

{#if reviewers}
## 👀 Requested Reviewers

{reviewers:mentions}
{/if}

---

{#if assignees}
## 📋 Assignees

{assignees:mentions}
{/if}

---

## 🔎 Review Checklist

- [ ] Code follows project standards
- [ ] Tests added or updated
- [ ] Documentation updated
- [ ] No secrets or credentials included
- [ ] Changes scoped appropriately
- [ ] Commit messages are clear

---

## 🔗 References

- PR Link: {url}
- Source Branch: {branch}
- Target Branch: {base}

---

## 🤖 Automation Context

This comment was generated automatically using the PR template engine.

**Debug info**

- Author: {author}
- PR: {number}
- Repo: {repo}
- Owner: {owner}
- Size: {size}
- Files: {changed_files}

---

Thanks @{author} for contributing 🎉
