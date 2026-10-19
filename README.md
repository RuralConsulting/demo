# Selwyn Farm Atlas (demo, encrypted)

The page at https://demo.ruralconsulting.co.nz. `index.html` holds only a sign-in box and the dashboard encrypted
with AES-256-GCM (key from the password via PBKDF2-SHA256, 600,000 rounds): without the password nothing in it can be
read. It's built in the private `canterbury-farm-dashboard` repo (`build/protect_site.py`); don't edit it here.
