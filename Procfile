web: gunicorn runp-heroku:app
init: python db_create.py && python scrapers/scrape_all
upgrade: python db_upgrade.py && python scrapers/scrape_update