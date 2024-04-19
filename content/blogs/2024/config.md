---
title: "Configuration"
date: 2024-04-19
description: "Configure your website using this guide." 
type: posts
url: "/config"
---

Here is what you need to know to configure this theme for your website: 

```bash
baseURL = "davlux.mansoorbarri.com"
languageCode = 'en-us'
title = "Davlux"
```

- `baseURL`: domain where your website will be deployed. Change it accordingly 
- `languageCode`: language of the code base. For most people, leave it as it is. 
- `title`: universal title for the website. Change it accordingly

```bash 
[menu]
  [[menu.main]]
    name = "blogs"
    url = "/blogs"
    weight = 1

  [[menu.main]]
    name = "tags"
    url = "/tags"
    weight = 2

  [[menu.main]]
    name = "rss"
    url = "/rss"
    weight = 3
```

here set the navbar menus 
- `name`: the title of the menu which is displayed to the user
- `url`: URL for the menu item
- `weight`: weight of the menu item. This uses Hugo's menu, more on this: https://gohugo.io/content-management/menus/

```bash
[params]
    wiki = "likh."
    hero = "a **hugo** theme, made with **Tailwind**."
    footer = "Davlux • 2024"
    mainSections = ["blogs"]
    projects = [    
        {name = "CS-Hugo", url = "https://github.com/mansoorbarri/coming-soon/", description = "A coming soon landing page made with Hugo"},       
        {name = "Hugo-Validator", url = "https://github.com/mansoorbarri/hugo-validator", description = "A theme submission validation script for Hugo"},       
        {name = "Aiman", url = "https://example.com", description = "Aiman Peman"},     
    ]
    socials = [        
    {name = "github", username = "mansorbarri"},       
    {name = "linkedin", username = "in/mansoorbarri"},       
    {name = "twitter", username = "mansoorbarri"},     
    ]
```

- `wiki`: shows up on the below the title. 
- `hero`: main description for the website.
- `footer`: footer text for the website.
- `mainSections`: main sections that will be part of the website. Can be more than one by adding the sections here like so: 
```bash 
mainSections: ["blogs", "newsletter", "floral"]
```
- `projects`: this populates the *projects* section on the landing page. 
- `socials`: populates the social icons.