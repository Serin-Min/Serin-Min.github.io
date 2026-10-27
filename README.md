# serin-min.github.io

Personal academic website of Serin Min. Live at https://serin-min.github.io

Plain HTML and one stylesheet. No theme, no build step beyond the GitHub Pages workflow.

| Path | Contents |
| --- | --- |
| `index.html` | Home |
| `projects.html` | Projects, grouped by research area |
| `publications.html` | Journal articles and manuscripts under review |
| `conferences.html` | Conference papers and presentations |
| `cv.html` | Curriculum vitae |
| `assets/style.css` | All styling |
| `images/projects/` | Project images, 16:10 crop |
| `files/` | CV PDF |

## Editing

Each page is a single HTML file. To add a publication, copy an existing
`<article class="pitem">` block and change the text. To add a project, copy an
`<article class="proj">` block.

Colors, type, and spacing live in `assets/style.css` under `:root`.
