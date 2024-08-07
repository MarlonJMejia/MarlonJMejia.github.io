* Create HTML

```bash
pandoc -s --css=styling.css --metadata pagetitle="Marlon Mejia" -V lang=en -V highlighting-css= --mathjax -f markdown+smart resume.md -o resume.html
```

* Create all

```bash
for i in html pdf docx; do  echo "resume.${i}" && pandoc -s --css=styling.css --metadata pagetitle="Marlon Mejia" -V lang=en -V highlighting-css= --mathjax -f markdown+smart resume.md -o "resume.${i}"; done
```
