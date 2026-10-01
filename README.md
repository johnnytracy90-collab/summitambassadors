# Summit Ambassador Hub: website package

A ready-to-publish copy of the Summit Ambassador Hub page: the program overview, four forms, and the document library. It is plain HTML, so it works on GitHub Pages or any ordinary web host.

## What is in this folder

| Item | What it is |
|---|---|
| `index.html` | The whole page. All of the text can be edited in any text editor. |
| `assets/` | The Summit Ambassador patch, the Summit logos, and the bear graphic. |
| `docs/` | The seven documents the page links to (six PDFs and the PowerPoint). |
| `robots.txt` | Asks search engines not to list the site while it is a temporary page. |

## Publish it with GitHub Pages (no software needed)

1. Sign in at github.com. If you do not have an account, create one. If your council or Scouting America already has a GitHub organization, check with your web team about hosting it there instead.
2. Select **New repository**. Give it a short name such as `summit-ambassadors`. Choose **Public**. Leave "Add a README file" **unchecked**. Select **Create repository**.
3. On the empty repository page, select **uploading an existing file**.
4. Unzip this package on your computer. Open the unzipped folder, select **everything inside it** (`index.html`, `README.md`, `robots.txt`, the `assets` folder, and the `docs` folder), and drag it all into the browser window. Wait for the uploads to finish. The largest file is the 14 MB PowerPoint, which is under GitHub's 25 MB browser-upload limit.
5. Select **Commit changes**.
6. Go to **Settings**, then **Pages**. Under "Build and deployment," set **Source** to **Deploy from a branch**, set the branch to **main** and the folder to **/ (root)**, then select **Save**.
7. Wait one to three minutes and refresh. Your site address will appear at the top of the Pages screen. It looks like `https://YOUR-ACCOUNT.github.io/summit-ambassadors/`.

## Updating it later

- **Replace a document:** in the repository, open the `docs` folder, choose **Add file, then Upload files**, and upload the new version with the **same file name**. The page picks it up automatically.
- **Edit text:** open `index.html`, select the pencil icon, make your change, and commit. Changes show up in about a minute.
- **Add a new document:** upload it to `docs`, then add a link to it in `index.html` next to the existing document cards.

## Before you publish: please check

- **This site will be public.** On GitHub's free plan, Pages sites are public, and anyone with the link can open them, including the "For ambassadors" documents (orientation, elevator pitch, presentation, checklist) and the contact details on the page. Private Pages sites need a paid GitHub plan; check GitHub's current plans.
- **Search engines are asked to skip it.** This is a request, not security. It does not make the page private.
- **Approvals.** Have your web or marketing team confirm that the logos, the patch, and the documents may be posted on this site, and that the forms are acceptable for collecting names, phone numbers, and Scouting IDs.
- **Placeholder.** The Library has a dashed "More coming soon" card with bracketed text for the Ambassador Handbook, marketing kit, talking points, and F.A.Q.s. Replace or remove it when those are ready.
- **Contact details.** The email address (Johnny.Tracy@scouting.org), phone number (304-465-2800), and address appear on the page. Confirm that they are the ones you want public.
- **Presenter details.** The PowerPoint's title slide and last slide carry Johnny Tracy's name and contact information. Ambassadors need to replace them.
- **Two items to settle in the source documents.** The elevator pitch says the five high-adventure experiences are for Scouts thirteen and up, while the orientation lists New River, A.T.V., and Marksman as fourteen and up. The Suggested Activity Checklist footer reads "25*46" where the ZIP code should be 25846.

## How the forms work

Each form checks the required fields, shows a review screen, and then offers an **Open email** button that creates a message to Johnny.Tracy@scouting.org. The person still has to press Send in their email app. There is also a **Copy message** button as a backup.

This is a stopgap. A form tool such as Microsoft Forms or Google Forms (or whatever your organization approves) can collect responses automatically and keep a record, with no email step. Ask your web team about connecting one.

## Fonts and the internet

The page loads two free fonts (Montserrat and Public Sans) from Google Fonts. If the fonts cannot load, the page falls back to the visitor's standard system fonts and still works.
