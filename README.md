# SUNINVEST D.O.O.
Official website

#### Development
```
jekyll s
docker-compose up -d
open http://localhost/
```

#### Deploy
```
JEKYLL_ENV=production jekyll build
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
```
