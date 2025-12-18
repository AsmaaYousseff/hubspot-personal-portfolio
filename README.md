# HubSpot Personal Portfolio

A custom personal portfolio website built using **HubSpot CMS**, developed with custom modules and managed locally using the **HubSpot CLI**. This project demonstrates hands-on experience with HubSpot CMS development, modular design, and version control using Git & GitHub.

---

## Project Overview

This portfolio was originally created directly inside **HubSpot Design Manager**, then fetched locally using the HubSpot CLI and uploaded to GitHub for version control and showcasing development work.

The project includes:

* Custom HubSpot CMS theme
* Reusable custom modules
* Structured templates
* Full local ↔ HubSpot sync workflow

---

## Features

* Custom HubSpot CMS **Theme**
* Modular components (Hero, About Me, Skills, Projects, etc.)
* Editable fields via HubSpot CMS editor
* Clean, organized file structure
* GitHub version control

---

## Project Structure

```
personal_portfolio/
│
├── modules/
│   ├── hero.module/
│   ├── about me.module/
│   ├── skills.module/
│   ├── Projects.module/
│   ├── work_experience.module/
│   ├── education.module/
│   ├── Contacts.module/
│   ├── header.module/
│   └── footer.module/
│
├── template/
│   └── template.html
│
├── theme.json
└── fields.json
```

---

## Technologies Used

* **HubSpot CMS**
* **HubSpot CLI**
* **HTML / CSS**
* **HubL (HubSpot Markup Language)**
* **Git & GitHub**

---

## Demo Video
![Quick Preview](./assets/demo.gif)

[▶ Full Demo Video](https://drive.google.com/file/d/1e24wJEv88VGG4jYN8S3l4IOJEo7wLJEp/view?usp=drive_link)

---

## Documentation
[View Documentation](https://docs.google.com/document/d/12nE_xJ-bIDwvKZJOwaIjnLJJu0tjuxLx/edit?usp=sharing&ouid=105418867781840247072&rtpof=true&sd=true)

---

## Development Workflow

### Fetch changes from HubSpot (online → local)

```bash
hs cms fetch / .
```

### Watch local changes and auto-upload to HubSpot

```bash
hs cms watch personal_portfolio
```

### Push changes to GitHub

```bash
git add .
git commit -m "Update portfolio"
git push
```

---

## Notes

* HubSpot online edits **do not sync automatically** to local files.
* Always run `hs cms fetch` after editing directly in HubSpot.
* GitHub only tracks local files.

---

## Author

**Asmaa Youssef**
HubSpot CMS Developer

* GitHub: [https://github.com/AsmaaYousseff](https://github.com/AsmaaYousseff)
* LinkedIn: [www.linkedin.com/in/asmaa-youssef-7124052a4](www.linkedin.com/in/asmaa-youssef-7124052a4)
* Portfolio: [https://147152241.hs-sites-eu1.com/en/personal-portfolio](https://147152241.hs-sites-eu1.com/en/personal-portfolio)

---

## License

This project is for personal and educational use.
