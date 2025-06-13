# puppeteer-test
Temp example using puppeteer with dbos.

Make sure to increase VM memory:
```
dbos-cloud app register -d <your_database>
dbos-cloud app update --executors-memory-mib=2500
dbos-cloud app deploy
```

Then visit `/screenshot` to see a snap of wikipedia.org
