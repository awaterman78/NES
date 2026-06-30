TonyNES GitHub Pages Deploy Fix v0.4.3

Upload these four files to the ROOT of your GitHub Pages branch:
- index.html
- player.html
- manifest.webmanifest
- .nojekyll

Important:
- Do not upload the zip itself.
- Do not upload the folder itself.
- On iPhone GitHub, hidden dotfiles can be awkward. If .nojekyll does not show in the picker, use the GitHub web editor:
  Add file
  Create new file
  Name it exactly: .nojekyll
  Leave the file empty
  Commit changes

Then wait for GitHub Pages to redeploy.
