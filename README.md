# Steady — DBT Diary Card Maker

Steady is a simple, private diary card maker for DBT practice. It guides you through a short daily check-in, organizes your answers into a weekly diary card, and tracks which DBT skills you practiced.

The finished diary card contains two tables:

1. Your personalized tracking areas and daily answers
2. Your DBT skills practice for the week

You can print the completed diary card, save it as a PDF, or share it with your therapist.

> Steady is a personal reflection tool, not medical advice or an emergency service. If you are in immediate danger or may act on thoughts of harming yourself, contact local emergency services or a crisis service in your area.

## Getting started

Open `index.html` in a web browser. You do not need to create an account.

### 1. Add your tracking areas

Open **Settings** and select **Add tracking area** for each thing you want to notice during the week.

Examples might include an emotion, urge, behavior, habit, or personal goal. You choose what is useful to you—the app begins with a blank list and does not include anyone else's tracking areas.

For each area, choose an answer style:

- **Intensity 0–5** for emotions, urges, or symptoms
- **Yes / No + note** for habits, goals, and behaviors
- **Written reflection** for an open-ended prompt

You can add, remove, rename, or change these areas at any time. Select **Save settings** when you are finished.

You may also enter your therapist's email address. This is optional. Steady will never send anything automatically.

### 2. Complete a daily check-in

Open **Check-in** and answer the questions one at a time. After your personalized questions, you can select any DBT skills you practiced and add an optional final note.

Select **Finish check-in** to add the day to your diary card. You can reopen the check-in on the same day to review or update it.

### 3. Review your diary card

Open **Diary card** to see the current Thursday–Wednesday week. Your answers appear in the first table, and the skills you selected appear in the DBT Skills Tracking table.

### 4. Save or share it

From the Diary Card page:

- Select **Print / Save PDF** to create a clean, shareable document containing both tables.
- Select **Email** to open your email app with your therapist's address filled in. Attach the PDF you saved.
- Select **Share** to use your browser or device's sharing options when supported.

## Privacy

Your settings and diary entries are stored only in your browser using local storage. They are not uploaded to GitHub or sent to a server.

This also means:

- Clearing browser data may erase your entries.
- A different browser or device will have a separate diary card.
- Other people using the same browser profile may be able to open the app and see its saved entries.
- Saving a PDF regularly is a good way to keep your weekly records.

## Publish your own copy with GitHub Pages

Upload these files to the root of a GitHub repository:

- `index.html`
- `styles.css`
- `app.js`
- `README.md`

In the repository, open **Settings → Pages**. Choose to deploy from your main branch and its root folder, then save. GitHub will provide a public link to the app.

The public app starts blank for every new browser. Personal tracking areas and answers are not stored in the project files.

## Project files

- `index.html` contains the app's pages and structure.
- `styles.css` contains the visual design and printable document layout.
- `app.js` manages settings, daily interviews, local storage, weekly tables, and sharing.

No installation, build process, database, or external dependency is required.
