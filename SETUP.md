# Your pixel GitHub profile

This package includes the animated room, custom vector header and buttons, interactive expandable sections, and your original resume PDF.

## Upload in the browser

1. Sign into GitHub and open https://github.com/new.
2. Create a PUBLIC repository named exactly Shivansh-Kumar-007 under your account. Enable Add README. If this repository already exists, use it instead.
3. Unzip this package.
4. Open the repository and choose Add file > Upload files.
5. Drag README.md and the entire assets and resume folders into the upload area. Keep those exact folder names. Upload their contents directly at the repository root, without an outer github-profile folder.
6. Commit the changes to the main branch.
7. Open https://github.com/Shivansh-Kumar-007 to see your profile.

Keep a backup of an existing README before replacing it. SETUP.md and ARTWORK.md are optional reference files and do not need to be uploaded.

If dragging folders does not retain their structure, first choose Add file > Create new file, type assets/.gitkeep, and commit. Open assets and upload the artwork files there. Repeat with resume/.gitkeep and upload Shivansh-Kumar-Resume.pdf inside resume. Finally edit the root README.md and paste in the supplied README content.

## What visitors can do

- Click the custom pixel buttons to jump to projects or skills, email you, or get your resume.
- Open and close each project and skill category.
- Follow links to Unibloom and your public repositories.
- See the looping room animation, a floating pixel character, blinking status light, and moving resume download arrow.

These are GitHub-supported links and expandable details, plus animated image assets. The README does not run JavaScript or behave like a playable game. Some previewers may show SVG animations as still images; the information remains readable.

## Resume download

The PDF is already included at:

resume/Shivansh-Kumar-Resume.pdf

The download buttons point to the raw PDF in your profile repository on the main branch. They become usable AFTER the files are committed. A separate View resume link opens GitHub's PDF viewer. Some browsers open PDF files in a tab; visitors can save them using the browser's download control.

If your default branch is not main, replace /refs/heads/main/ in BOTH download button URLs with /refs/heads/YOUR-BRANCH/ in README.md.

When updating your resume, replace the PDF while keeping the same filename. The buttons will continue to work.

The PDF is the original file you uploaded, including its contact details. It will be public when uploaded to your public profile repository.

## Optional: still room

Change assets/developer-room.gif to assets/developer-room.png in README.md if you prefer the still artwork.

## Check after uploading

- The profile displays your name and room artwork.
- Projects and inventory sections expand when clicked.
- Both resume download buttons open the PDF.
- The View resume link and email links work.
- Performance figures and project descriptions are accurate for public sharing.

## Files

- README.md — profile page
- assets/ — all artwork, including custom SVG navigation and status panels
- resume/Shivansh-Kumar-Resume.pdf — original resume
- ARTWORK.md — prompt and artwork notes
- SETUP.md — this guide

Reference: https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme
Expandable sections: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections
