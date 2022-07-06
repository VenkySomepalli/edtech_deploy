#web: gunicorn -w 4 -k uvicorn.workers.UvicornWorkers main:app
web: uvicorn main:app --host=0.0.0.0 --port=${PORT}
