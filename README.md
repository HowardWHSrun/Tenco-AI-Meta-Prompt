# Tenco-AI-Meta-Prompt (TBW Workspace)

This repository contains Turner Engineering's TBW workspace: proposals, procedures, reports, task matrices, and supporting reference material, along with the Tenco AI meta prompt and style guide. It is organized for easy browsing, quick search, and future expansion.

## 1) Overview
- Purpose: Centralize project documents and templates so they are versioned, searchable, and shareable.
- Scope: PDFs, DOC/DOCX, XLSX task matrices (redacted), and guidance files used for proposals, procedures, reports, and EMI/EMC work.
- Audience: Turner Engineering staff and collaborators with access to this repository.

## 2) Repository Structure
- Root files:
  - `Tenco AI Meta Prompt.md`: Meta prompt and conventions used when working with AI assistants.
  - `Tenco Style Guide.pdf`: House style guide for writing and formatting.
  - `Caltrain Power Presentation.pdf`: Reference presentation.
  - `IEEE ASME Vycon FESS Paper 1-13-05.doc`, `IEEE EMC Magazine Spring 2012 Rail Transit EMI-EMC.pdf`: Reference papers.
- Directories:
  - `Proposals/`: Procurement questions, proposal drafts, and finalized PDFs.
  - `Reports/`: Procedures, results, and reports (PDF/DOC) for projects (e.g., Caltrain, MTA/NYCT, TRA, Penn Station).
  - `Task Matrices/`: Redacted task matrices and estimates (XLSX + TXT) for reference across projects and clients.

Note: Many files are binary (PDF, DOCX, XLSX). They are committed directly for ease of access.

## 3) How to Use
- Browse: Navigate directories to open documents. On macOS, press Space for Quick Look previews.
- Search:
  - Finder: use filename/keyword search.
  - Git: `git grep -n "keyword"` (effective for `.txt`, `.md`), or open binaries with native apps.
- Open & Edit: Use your native applications (Word, Excel, Acrobat). Save changes, then commit.

## 4) Updating the Repository
- Pull latest changes before editing:
```bash
git pull
```
- Add new or modified files:
```bash
git add -A
git commit -m "Update: <short description>"
git push
```
- Large binary additions: if many large files will be added, consider Git LFS in the future.

## 5) Task Matrices Guidance
- Use the existing matrices as references when creating new estimates/scope.
- Keep both `.xlsx` and a `.txt` export when possible for diffability.
- Name files with clear client, scope, and date stamps for traceability.

## 6) Notes & Expectations
- This repository is intended for internal/partner use. Remove or redact sensitive information before committing.
- Prefer descriptive commit messages and keep the directory structure consistent.

## 7) Repository URL
- GitHub: https://github.com/HowardWHSrun/Tenco-AI-Meta-Prompt

If you have questions or need structural updates, open an issue or propose an edit via pull request.
