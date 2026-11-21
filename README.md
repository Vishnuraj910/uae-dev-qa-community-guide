# UAE | MENA Software Engineers & QA Community Handbook

A searchable guide to the community’s guidelines and code of conduct, WhatsApp groups, and upcoming meetups. The community is free, nonprofit, and open to software professionals and students across the UAE and MENA.

[Read the handbook](https://uae-mena-community-handbook.vercel.app/) · [Find a meetup](https://luma.com/uaesoftwareengineers) · [Contact a community admin](https://uae-mena-community-handbook.vercel.app/#admins)

## What’s in the handbook

- **Community guidelines and code of conduct** with plain-language highlights, searchable sections, full policy wording, and a download of the original PDF.
- **WhatsApp group directory** with each group’s purpose. New members attend an in-person meetup first and are added by a moderator.
- **Upcoming events** from the community’s live Luma calendar. Event details and registration are managed on Luma.

The policy text comes from *Community Guidelines & Code of Conduct*, version 2.0, dated November 19, 2026. The PDF is available from the handbook footer.

## Run locally

The site uses HTML, CSS, and vanilla JavaScript. There are no dependencies to install, no build step, and no environment variables.

```sh
git clone https://github.com/Vishnuraj910/uae-dev-qa-community-guide.git
cd uae-dev-qa-community-guide
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000). The event calendar and external links require an internet connection.

## Repository layout

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Handbook content, styles, search, section navigation, and Luma embed |
| [`community-handbook-banner.jpg`](community-handbook-banner.jpg) | Link-preview image used by messaging and social platforms |
| [`favicon.ico`](favicon.ico) and [`apple-touch-icon.png`](apple-touch-icon.png) | Browser tab and home-screen icons |
| [`vercel.json`](vercel.json) | Static deployment configuration for Vercel |

## Contributing

Open a [GitHub issue](https://github.com/Vishnuraj910/uae-dev-qa-community-guide/issues) for a bug, accessibility issue, broken link, or suggested improvement. Include the affected section or URL, what you expected, and what happened. To submit a fix, fork the repository, make a focused change on a branch, then open a pull request against `main`.

- Cite the approved community source for policy changes, including the document version and page when available. Ask a community admin to confirm changes to policy wording, moderation rules, membership, or official links.
- Preview changed sections on a narrow and a wide screen. For changes to interactive content, check keyboard navigation, search, and direct section links. For sharing changes, check that the page metadata points to a publicly reachable banner.
- Keep private invite links, credentials, personal information, and identifying screenshots out of issues and pull requests.

## Community conduct

Use English, keep discussions respectful and constructive, and avoid promotion and unsolicited direct messages. Follow the [community code of conduct](https://uae-mena-community-handbook.vercel.app/#conduct). Report harassment, unwanted messages, or other sensitive incidents privately to a [community admin](https://uae-mena-community-handbook.vercel.app/#admins).

## Licensing

This repository is public and currently has no open-source license. The maintainers need to select and add a license before offering the site code for open-source reuse. The community handbook text, logo, and meetup photos may have separate rights holders and should only be included in a license grant with their permission. See [GitHub’s guidance on licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).
