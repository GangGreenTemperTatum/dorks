# **Google Dorking for API's and API Documentation Passive Recon:**

### Find API artifacts exposed on a web server, like keys and config:

```
intitle:"index of" intext:"api"
```

### Search a target domain site for the keywords of the subdomain URL including "admin" or "login" and ".php" or ".asp":

```
site:*.x.com inurl:”*admin | login” | inurl:.php | .asp
```

### Find interesting API directories:

```
inurl:"/api/*" intext:"index of"
```

### Find possible environment variables relating to API, including keys and tokens:

```
intext:api filetype:env
```

### Find potential API keys:

```
intitle:"index of" api_key OR "api key" OR apiKey -pool
```

### Find API keys in interesting files.:

```
intext:APIKey ext:js | xml | yaml | txt | conf | py intitle:"index of"
```

### Find potential API configs:

```
intitle:"index of" "api.yaml"
```

### Find log files that may be leaking information about API artifacts:

```
"api" ext:log
```

### :

```

```
