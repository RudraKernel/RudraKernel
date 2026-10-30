# Set up your GitHub profile (10 minutes)

## 1. Create the special profile repo
1. github.com/new  ->  Repository name: **RudraKernel** (exactly your username)  ->  **Public**. Leave "Add a README file" unticked, because this folder already has one.
2. Upload everything in this folder (README.md, SETUP.md optional, the `assets` folder and the `.github` folder).
   Drag and drop works, but make sure the hidden `.github/workflows/snake.yml` goes up too.
   (Easiest: install Git, then `git init`, `git add .`, `git commit -m "profile"`, `git branch -M main`, `git remote add origin https://github.com/RudraKernel/RudraKernel.git`, `git push -u origin main`.)
3. The README now shows on your profile page.

## 2. Turn on the animated contribution snake
1. Repo > **Settings > Actions > General > Workflow permissions** > choose **Read and write permissions** > Save.
2. Repo > **Actions** > "Generate contribution snake" > **Run workflow**. Wait about a minute.
3. A branch named **output** appears with the snake images. The README already points to it. It refreshes every 12 hours.

## 3. Polish the rest of the profile
- **Bio** (edit profile): `B.Tech IT '30 · Developer · Esports IGL · Filmmaker · Mumbai`
- **Location:** Mumbai. **Website:** your portfolio link once it is live.
- **Status** (smiley icon on profile): `Building my 3D portfolio` or `Learning C`.
- **Social accounts** (edit profile > Social accounts): LinkedIn and Instagram links.
- **Pin 4 repos** (Customize your pins): R-s-Portfolio, Ajeya-26, R-s-Poems, first-pr-festival.
- **Repo descriptions + topics:** add a one-line description and topics (html, css, javascript, portfolio) to each repo. It makes the pinned cards look finished.
- **Avatar:** a clean, well-lit photo or the dark "RK" mark; keep it square.

## 4. Edit the content
- Swap the project descriptions in README.md as your repos grow.
- The colours in `assets/*.svg` use #ff5a36 (orange) on near-black, matching your portfolio. Search and replace that value to change the accent.
