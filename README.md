# Telegram Bot API image

This is an OCI image that runs the telegram bot api (TBA) server and also includes a custom setup (via nginx) to retrieve telegram files in the same way the oficial api does (ex: `http://tba.local/file/bot{{ BOTTOKEN }}/{{ PATH }}`)
