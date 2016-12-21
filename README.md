# django-nginx

Docker image to serve static files in front of django and forward everything else to the linked gunicorn container.

The static files directory must be mounted to `/src/etc/static`.

The traffic will be forwarded to `http://web:8000`.
