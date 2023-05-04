# **SQL-Injection based dorks:**

### SQL Errors:

```
site:target.com intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()"
```

### SQLi Dork:

```
site:target.com intext:"sql syntax near" |  intext:"incorrect syntax near"
```

### Confirmed with "waitfor delay'0:0:15'--:

```
site:target.com intext:"sql syntax near" |
intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()"
```
