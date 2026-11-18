# Article cover illustrations

Created November 9, 2026 using the built-in **image_gen** tool and the imagegen skill. Status: **local review; unpublished**.

Ten distinct editorial concepts accompany the [full article drafts](../drafts/README.md). The palette follows the existing Skynet Jobs covers: charcoal/navy with cyan/teal and restrained amber. The illustrations have no article text, logos, statistical labels, or imitation data charts.

## Assets and concepts

| Asset | Article concept |
| --- | --- |
| `01-why-the-jobs-numbers-disagree.webp` | Optical prisms separate perspectives on the labor market |
| `02-tech-hiring-entry-level.webp` | Access to the first steps of a career staircase |
| `03-banking-ai-attribution.webp` | Inspecting the separate mechanisms inside restructuring |
| `04-ai-and-the-longer-workday.webp` | Saved time flowing into additional work and coordination |
| `05-coding-productivity-reset.webp` | Raw output passing inspection before becoming useful work |
| `06-healthcare-paperwork.webp` | Paperwork relief creating room for a conversation |
| `07-legal-ai-economics.webp` | The allocation of value among expertise, time, and clients |
| `08-robots-beyond-the-demo.webp` | Practical material handling and industrial automation |
| `09-freelance-volume-and-value.webp` | Assignment volume and the value of completed projects |
| `10-beyond-just-reskill.webp` | A career bridge requiring several tangible supports |

## Provenance and use

- [Full prompt set](generation-prompts.json) records a separate prompt for each cover and the common art direction.
- WebP assets are compressed from generated PNG outputs without changing their visual content. Original generator outputs remain in the generator's default storage; the project consumes the copies in this directory.
- [Asset manifest](asset-manifest.json) records final dimensions, byte sizes, and SHA-256 checksums.
- Draft frontmatter supplies relative cover paths, descriptive alt text, and an explicit AI-illustration caption.
- These are conceptual editorial illustrations, not photographs of actual people, institutions, products, or reported deployments. They are not research evidence, workflow diagrams, or medical instructions.
- The local Vite review server reads the files directly from this directory. They are intentionally outside the website's `public/` folder and are excluded from production builds until a separate publication decision.

Review at [http://localhost:8080/analysis/review](http://localhost:8080/analysis/review). Use **Refresh files** to pick up metadata changes. The local page displays covers in the article cards and above each article's text.
