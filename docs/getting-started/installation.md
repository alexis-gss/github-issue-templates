---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 📥 Installation

Add the Github Project Template as a remote template in your project :

```
git remote add template https://github.com/alexis-gss/github-project-template.git
```

Then pull all modification of the theme :

```
git fetch --all
```

Finally, merge modifications to your main branch :

```
git merge template/master --allow-unrelated-histories
```

You can now use and customize the Github Project Template.
