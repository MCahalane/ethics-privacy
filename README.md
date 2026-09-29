# Ethics and Privacy in Information Systems

An interactive Day 5 learning resource for an introductory Essentials of Information Systems course. It is designed for students with basic IT and IS knowledge and uses everyday examples, contemporary AI cases, videos, audio discussions, and formative knowledge checks.

## Lesson contents

1. Ethics, law, privacy, and security
2. Privacy, accuracy, property, and accessibility
3. Responsible data handling, profiling, consent, and surveillance
4. Ethical decision making, responsibility, accountability, and liability
5. AI cases involving Australia's Medicare statistics portal and Hugging Face, plus an optional autonomous-vehicle ethics case
6. A campus café design activity and exit ticket

The site also includes source references and instructor notes. The café and everyday scenarios are fictional. Contemporary incident summaries reflect evidence checked on September 30, 2026 and should be reviewed before future teaching.

## Files

| File or folder | Purpose |
| --- | --- |
| `index.html` | Complete lesson, styles, navigation, and interactive behavior |
| `assets/` | Six compact AI-generated learning illustrations in WebP format |
| `audio/openai-sandbox.m4a` | Instructor-supplied sandbox discussion, approximately 1 minute 45 seconds |
| `audio/autonomous-vehicle-debate.m4a` | Instructor-supplied vehicle ethics debate, approximately 5 minutes 45 seconds |
| `.nojekyll` | Tells GitHub Pages to serve the static files without Jekyll processing |
| `README.md` | Setup and maintenance instructions |

Keep the folder structure intact. Images and audio use relative paths so the site can run under a GitHub Pages repository URL.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `ethics-privacy`. A public repository supports GitHub Pages on GitHub Free.
2. Unzip the website package on your computer.
3. Upload the extracted contents to the repository. Place `index.html`, `assets/`, `audio/`, `.nojekyll`, and this README at the repository's top level. Upload the files and folders, not the ZIP or an enclosing folder.
4. Commit the upload to the `main` branch.
5. Open **Settings → Pages** in the repository.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select **main** and **/(root)**, then select **Save**.
8. Wait for deployment to finish. The Pages settings display the published URL.

The URL will normally be:

`https://YOUR-USERNAME.github.io/ethics-privacy/`

Replace `YOUR-USERNAME` and the repository name with your actual values. No npm installation, build command, database, API key, or application server is needed.

GitHub's setup guidance: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Preview locally

You can open `index.html` directly for a basic preview. A local web server gives a closer match to hosted behavior, particularly for browser storage and media.

If Python is installed, run this command from the folder containing `index.html`:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser. Use `python` instead of `python3` if that is your system's Python command. Press Ctrl+C in the terminal to stop the server.

YouTube playback requires an internet connection. The written lesson remains usable without playing the videos.

## Learning features and data handling

- Six ungraded, retryable knowledge checks with explanatory feedback
- Progress and activity drafts stored locally in the student's browser
- A worksheet download that includes the student's entered responses
- A read-all view and print option for the full lesson
- Responsive images with alternative text and explanatory captions
- YouTube players loaded only after the student selects **Load video**, with no autoplay
- Two native audio players with playback controls and separate audio links

The lesson code does not send student names, grades, progress, or worksheet responses to an application server. Local browser storage persists until cleared or reset. Moving to a new hosting address does not transfer saved progress or drafts.

Loading a YouTube player connects to YouTube. The site uses YouTube's privacy-enhanced embed domain, but this does not mean that playback involves no data processing. GitHub and other hosting providers may also process normal access information. The written cases are not verbatim transcripts of the supplied audio.

## Update the site

Edit `index.html` to change lesson text, links, video cards, or activities. Replace images in `assets/` or recordings in `audio/` when needed, updating the matching paths and descriptions if filenames change.

Commit the revised files to the configured publishing branch. GitHub Pages will publish the update. After publishing, check navigation, image loading, audio, videos, knowledge checks, and worksheet downloads.

GitHub Pages and the ChatGPT-hosted site are separate publications. Updating one does not automatically update the other.

## Teaching and source notes

Use the references inside the lesson when discussing claims. Distinguish government statements, company accounts, independent reporting, and classroom interpretation.

- Australia's Medicare statistics portal is different from the U.S. Medicare program. Unauthorized access does not establish that individual patient records were stolen.
- The Hugging Face case concerns internal research and evaluation activity; it is not an example of ordinary chatbot use.
- The autonomous-vehicle collision dilemma is hypothetical. Its certainty assumptions do not describe how real vehicles predict crash outcomes.
- The six images are AI-generated illustrations, not photographs of the incidents or screenshots of actual affected products.
- The audio recordings were supplied by the instructor as discussion aids. The linked videos remain hosted on YouTube.

The resource draws on introductory information ethics concepts, including PAPA and four ethical approaches, and extends them through contemporary examples. The site does not distribute the course textbook or reproduce its pages.

No blanket reuse license is declared for the package. Check relevant rights before redistributing supplied recordings or third-party material. No affiliation with or endorsement by the organizations discussed is implied.

## Troubleshooting

**The page is missing:** Check that `index.html` is at the top level of the selected publishing folder and that Pages is configured for the correct branch and folder.

**Images or audio are missing:** Confirm that `assets/` and `audio/` were uploaded and that filenames match exactly, including capitalization.

**A video does not play:** Use its direct YouTube link. Playback can be affected by network restrictions, browser settings, or the video owner's embedding settings.

**Old content still appears:** Check that the latest Pages deployment succeeded, then reload the page.

**Progress is missing:** Progress is specific to the browser and hosting address. Private browsing, clearing site data, or using another device may remove or change it.
