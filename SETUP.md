# Publish your GitHub profile

This folder is the source for your profile repository. GitHub displays the root
`README.md` on your profile when the public repository name matches your username:
**`Paraschawla21/Paraschawla21`**.

## Preview

Open `README.md` in your editor’s Markdown preview. Open `assets/hero.svg` in a
browser to inspect the banner at full size. The files are self-contained SVGs;
no build step is required. GitHub supports SVG images and their declarative
animations. The architecture diagram hides its moving dots for reduced motion.

## Publish

1. Sign in to **Paraschawla21** in your browser.
2. Create a **public** repository named **Paraschawla21** at
   <https://github.com/new>. Leave the initialization options unchecked.
3. Run these commands from this folder:

   ```bash
   git init -b main
   git add README.md assets SETUP.md
   git commit -m "Create personal GitHub profile"
   git remote add origin git@github-personal:Paraschawla21/Paraschawla21.git
   git push -u origin main
   ```

4. Visit <https://github.com/Paraschawla21> to see the profile README.

Your directory-based Git settings select your personal commit identity. The
`github-personal` SSH alias selects your personal GitHub authentication. The
GitHub CLI’s active work login does not affect the SSH push above.

## Finish the presentation

On your GitHub profile, select **Customize your pins**. Suggested repositories:

1. `government-business-registration-assistant`
2. `storiesbyakshat`
3. `LMS_Odyssey`
4. `react_portfolio`
5. `KYC-VERIFICATION-USING-BLOCKCHAIN`
6. `leetcode_gfg`

Suggested short bio:

> Full-stack engineer @ Bazaarvoice · Building web products & exploring useful AI · VIT Vellore · Bengaluru

The hero is an original code-and-systems illustration. If you later want a
portrait-led banner, you can replace `assets/hero.svg` and update its README image
description.

## Updating it

- Edit `README.md` to change your introduction, projects, and links.
- Edit the SVG files to change the banner, colors, or diagram.
- Core artwork lives in this repository. Only the social badges and toolbox
  icons use external image services; descriptive alt text accompanies each.
- Keep project descriptions and status labels current as you ship features.
- Normal pushes to this repository update the profile automatically.
