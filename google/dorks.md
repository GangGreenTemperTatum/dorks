# **Rules of Advanced Operators:**

### Exact match:

```
""""" (Quotes)
""Cannot read property 'map' of undefined"""
```

### "Search within specific site:

- Search a target domain site for the keywords of the subdomain URL including ""admin"" or ""login"" and "".php"" or "".asp"""

```
"site: (Search within specific site)
site:freecodecamp.org react
site:*.x.com inurl:”*admin | login” | inurl:.php | .asp"
```

### Exclude a term from search:

```
"- (Exclude)
how to write components in React -class"
```

### Search for a specific imagesize:

```
"imagesize:500x500
cute dog images imagesize:500x600"
```

### Search for a specific filetype:

```
"filetype:
reactjs tutorial filetype:pdf"
```

### Use wildcard to make searches:

```
"* (Wildcard)
The * of money"
```

### Use and|or logic operators:

```
"and|or
Angular and react
Angular or Python"
```

### Add a tag of after to represent the year of published document for filter:

- Add .. digits to represent a range

```
"AFTER:2020 , BEFORE:2022
React tutorial AFTER:2020 BEFORE:2022
React tutorial AFTER:2020..2021"
```

### Related Tag:

```
"related:
related:google.com"
```

### Add this tag to the URL bar to view Google's cached version of the website:

```
"cache:
cache:www.msn.com"
```

### (DEPRECATED) - Exact Match - Replaced by `""` (Quotes)

```
+
```
