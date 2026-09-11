APPLIED FINANCIAL CALCULATORS
GitHub Pages Deployment Package

Folder structure:
/
  index.html
  tvm/index.html
  financial-statements/index.html
  borrowing/index.html
  federal-tax/index.html

HOW TO DEPLOY
1. Create one GitHub repository, for example:
   applied-financial-calculators

2. Upload the CONTENTS of this folder to the root of the repository.
   Do not upload the outer folder as an extra nested level unless you intend to.

3. In GitHub:
   Settings -> Pages
   Choose "Deploy from a branch"
   Branch: main
   Folder: /(root)

4. Your landing page will be:
   https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

5. Students only need the landing-page URL.

CALCULATOR URLS
- /tvm/
- /financial-statements/
- /borrowing/
- /federal-tax/

MAINTENANCE
Each calculator remains independent. To update one calculator, replace only
that calculator's index.html file.

To add a new calculator:
1. Create a new folder at the repository root.
2. Put that calculator's index.html inside it.
3. Add a new card/link to the root index.html landing page.

NOTES
- A "Back to All Financial Calculators" link has been added to each calculator.
- The landing page includes topic filtering, search, and a "Which calculator
  should I use?" guide.


BRANDING
- Place the provided branding image in /assets/ttu-sfp-branding.png.
- Each calculator page references the shared branding image from the assets folder.
