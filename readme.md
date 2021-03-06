# EMBL-EBI Style Lab
This is a collaborative effort. The EMBL-EBI Style Lab is a place to communicate how we use visual identity, code, and language to make better and more accessible services -- it exists because of pan-EMBL-EBI collaboration.

## What is this, exactly?
The EMBL-EBI Style Lab is a collaborative space that also shares the latest guidance on how and what should be used to build visually and textually compliant EMBL-EBI websites, documents, and texts. It's partly about reinforcing our shared identity, but it's mostly about leveraging the best tools to build things faster and with fewer bugs, errors, and user experience issues.

### Contents of the EMBL-EBI Style Lab
- General styling
  - Our basic style guide (to be added)
  - Microsoft Word and PowerPoint templates (to be added)
  - Poster templates (to be added)
  - EMBL-EBI Logos  (to be added)
  - Fonts & icons (to be added)
  - Social media guidelines (to be added)
- Website specific
  - How to get started with the EBI Visual Framework (add link to guide)
  - How to use the EBI Icon fonts on a website (add link)
  - Boilerplate templates to get started (add link)
  - Reusable patterns (add link)
    - How to add a patter (See the guide at how-to.html)

---

## Are you a web developer?

### How do I develop on my local machine

1. Your computer needs:
  - [NodeJS](https://nodejs.org/en/)
  - [Git](https://git-scm.com/)
2. Get the git repo: `git clone https://github.com/ebiwd/ebi-style-lab.git`
  - If you've not yet installed bower (you may need to run with sudo): `npm install -g bower`
3. Then open the folder in your command line, and install the needed dependencies:
    ```bash
    cd EBI-Style-lab
    npm i
    bower i
    ```
4. Finally:
  - To develop: run `npm start` to start the project and watch for changes. It will open in your browser at http://localhost:8000.
  - To build for deployment: run `npm run build`

---

## Versioning

Relases are versioned according to the EBI Visual Framework being used. That is: while we uses the EBI Visual Framework v1.2, all EBI Style Lab releases will be v1.2.X



---

## Credit
The base CMS configuration and code examples are forked from ZURB Foundation Building Blocks.
