# SUNINVEST D.O.O.
Official website

#### Development
```
bundle exec jekyll s
docker-compose up -d
open http://localhost/
```

#### Deploy
```
JEKYLL_ENV=production bundle exec jekyll build
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d --build
```
