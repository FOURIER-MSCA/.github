# Contributing to the FOURIER GitHub organization

This guide applies to all repositories in the organization unless a repository has its own `CONTRIBUTING.md`.

## Adding a new research project

1. Ask an organization owner for member access (you need to be a FOURIER doctoral candidate or staff member).
2. Open the [`project-template`](https://github.com/<org-name>/project-template) repository and click **Use this template → Create a new repository**.
3. Set **Owner** to the FOURIER organization and choose a repository name (see naming below).
4. Start as **Private** while you set things up. Switch to **Public** once the checklist below is complete.
5. Fill in the `README.md`, `LICENSE` and `CITATION.cff` placeholders.
6. Ask an owner to add your repository to the projects table on the organization page.

### Repository naming

- Lowercase, words separated by hyphens: `crack-detection-uav`, not `Crack_Detection_UAV`
- Describe the topic, not the person
- For code accompanying a paper, you may add a short suffix: `crack-detection-uav-paper2027`

## Before making a repository public

- [ ] Your supervisor agrees to the release
- [ ] No unpublished results that you or your co-authors want to keep confidential
- [ ] No confidential data or information from industry partners or secondment hosts, unless they have agreed in writing
- [ ] No personal data, passwords, API keys or tokens (check the full history, not just the latest files)
- [ ] No copyrighted material such as publisher PDFs
- [ ] A licence is chosen (`LICENSE` file filled in)
- [ ] The README explains what the repository is and how to use it
- [ ] The EU funding acknowledgement is in the README

## Good practice

- Work on branches and merge via pull requests, even when working alone; it keeps the history readable.
- Write commit messages that say what the change does: `Add data loader for SHM sensor files`.
- Keep large data (> ~10 MB) out of Git. Archive it on Zenodo or an institutional repository and link it in `data/README.md`.
- When a paper is published, create a GitHub **release** and connect the repository to [Zenodo](https://zenodo.org/) to get a citable DOI.

## Questions

Open an issue in the [`.github`](https://github.com/<org-name>/.github) repository or contact an organization owner: <name>, <email>.
