web: gunicorn master:master --workers 4 --threads 4 --bind 0.0.0.0:$PORT --timeout 86400 --worker-class aiohttp.GunicornWebWorker & python -m bot.py
