The repository for www.ccampbell-moore.com, Catrin Campbell-Moore's academic website.

Created with [academic for hugo](https://sourcethemes.com/academic/).

See [readme for johannes-website](https://github.com/catrincm/johannes-website/blob/master/README.md) for instructions.


--------

- Update the `theme` file by pasting in the new version from https://github.com/wowchemy/wowchemy-hugo-themes
- Add to `exampleSite` from https://github.com/wowchemy/starter-hugo-academic


---------

Record of theme overwrites:

# Settings in params:
- Remove day from date_format
- Set `profile: false` to disable author profile at end of pages
- View for publication date
- How publications are viewed under project

# Added pronouns and title at end of contact,
Overwrite `layouts/partials/widgets/contact.html` to add part starting `{{ range $st.Params.personal_details }}`

# Adding jobs to education.
- Overwrite `layouts/partials/widgets/about.html` starting `{{ with $person.education }}`
- Change title to "Past Positions". I've done that manually, could also be done in `i18n`

# Draft papers
- Overwrite `layouts/section/publication.html` to add a link at the end to `See Drafts`
- Duplicate `layouts/section/publication.html` for `layouts/section/draft-papers.html`, removing selection
- In `config.yaml` have: `permalinks:  draft-papers: '/publication/:slug/` so the urls of drafts are consistent with those of papers.

# Date print
- Overwrite `layouts/partials/page_metadata.html` as https://github.com/catrincm/personal-website/commit/8b8ffaf349acdaa6fed0305ad93f5a8e3a9acd51 (though just the `date_print` part)

# Formatting of default list - used in tags.
- Overwrite `layouts/_default/list.html` based roughly on `layouts/project/single.html`.


# TODO:
- Remove the "Catrin Campbell-Moore" line from card. Only include co-authors and then say "with...".
