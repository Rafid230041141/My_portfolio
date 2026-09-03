# AI Tool Usage Log

## Tool used
**Claude** (Anthropic) — web chat interface, Claude Sonnet 5.

## What it was used for
Designing and coding the portfolio website (`index.html`, `style.css`, `script.js`),
drafting the README, and structuring the site so it's easy to extend with future
projects and achievements.

## Prompt history (chronological, as sent by the user)

1. Assignment brief pasted in full: instructions to build a personal portfolio
   website, host it via GitHub Pages, and document AI tool usage — including
   requirements (identity/contact info, projects/achievements, creative theme) and
   example reference portfolios.

2. Follow-up answers to clarifying questions about design direction:
   - Style preference: **Visually bold/creative**
   - Field/focus: **CS / Software Engineering**
   - Content readiness: **Content ready to share**

3. Personal/contact details provided:
   ```
   Name: MD AZIZUL HAKIM KHAN RAFID
   email: mdazizulhakimkhanrafid@gmail.com
   short bio: I am a university student currently studying in Islamic University
   of Technology (IUT). I am interested in problem solving and creating cool stuffs.
   Github: Rafid2300411141
   LinkedIn: www.linkedin.com/in/md-azizul-hakim-khan-rafid-3511483b1
   You can find one of my project which is forked in my github
   ```

4. Project repository link provided:
   `https://github.com/Rafid230041141/CSE_4302_Project`

5. Project description provided:
   "Object Oriented Programming course, we used C++ to build a school management
   system"

6. Uploaded a personal photo to be added to the site, and the actual project source
   code (`CSE_4302_Project-main.zip`) to verify and accurately describe the project
   (team size, contribution, build tooling), plus a request to add a visual
   representing "school" to the project card.

## What Claude generated
- Full site design concept (IDE/terminal theme: editor-tab navigation, typewriter
  terminal hero, git/terminal-styled project cards, log-style achievements section).
- All HTML, CSS, and JavaScript for the site.
- Profile photo integration (resized/optimized, added as a framed image in the hero).
- A custom inline SVG schoolhouse icon (drawn in the site's own accent colors,
  rather than an unlicensed stock photo) for the School Management System card.
- Corrected the project description after reading the actual uploaded source code —
  it's a 4-person team project using Meson/clang-tidy, with Rafid responsible for
  the User, Student, Teacher, and Admin classes.
- README with GitHub Pages deployment steps and instructions for adding future
  projects/achievements.
- This usage log.

## What was left to the human
- Verifying the GitHub username/link consistency (two slightly different usernames
  were provided across messages — profile link vs. project repo owner).
- Filling in real academic achievements/research once available (placeholder section
  included, clearly marked).
- Adding future projects as they're completed.
- Creating the actual GitHub repository, pushing the code, and enabling GitHub Pages.
