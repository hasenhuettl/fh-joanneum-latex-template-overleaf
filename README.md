# fh-joanneum-latex-template-overleaf
Latex Template for writing a Master Thesis in LaTeX for the Master Program Information Management at FH JOANNEUM Graz. 

This project is intended for and tested in Overleaf. Check out the initial project from [Stefan Leitner](https://github.com/stfnltnr/fh-joanneum-latex-template-vscode/tree/master) for VS Code extensions.

Overleaf is only recommended in the premium verson. The student plan costs €79 for one year. 

This fork builds on the initial project for adjustments, error fixes and improvements in structure and imported packages.

## Use the correct Compiler
- Open the project in Overleaf
- Click on Menu
- Under Settings set Compiler to "LuaLaTex"

## My citation workflow
This is the citation workflow that worked the best for me and I would recommend when working with Overleaf. However, this is by far not the only method, and should just be a suggestion for those who are just starting with overleaf and struggling with citations (like I was).

- Download and install a literature management program - I used [Zotero](https://www.zotero.org/)
- Download the Zotero Connector (Browser Plugin) - (Make sure no other plugins are interfering, check with [http://127.0.0.1:23119/connector/ping](http://127.0.0.1:23119/connector/ping) if your Browser can reach Zotero.)
- Download and install the Zotero [Better Bibtext Plugin](https://retorque.re/zotero-better-bibtex/installation/index.html)
- Open Zotero in your OS
  - Edit->Preferences->Sync->
    - Create Account
    - Link Account in Zotero application
    - Disable both File Syncing checkboxes (or you'll reach 300 mb limit soon)
  - Edit->Preferences->Export->
    - Item Format: Better BibTex Citation Key Quick Copy

This lets you Drag'n'Drop your literature as \cite{citationkey}

  - Tools->Better BibTeX->Preferences->Citation Keys->Automatically pin citation key after
    - Set to 1 second

This makes it, so you don't have to change your \cite{} in your text when you change things like the author later on.

- Now all that's left to do, is to [link your Zotero Library into Overleaf](https://www.overleaf.com/learn/how-to/How_to_link_your_Overleaf_account_to_Mendeley_and_Zotero)

## Using the workflow
- Add books via ISBN in Zotero
- Add online literature by clicking on the browser plugin
- Add missing information in Zotero (Second monitor appreciated)
- Switch to Overleaf
- Drag and drop the literature into where you want it to be cited
