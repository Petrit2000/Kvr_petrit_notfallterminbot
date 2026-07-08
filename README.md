# KVR Termin Alarm

Ky projekt kontrollon linkun e KVR-së dhe dërgon alarm në Telegram kur ndryshon statusi i terminit.

Linku i monitoruar:
https://stadt.muenchen.de/buergerservice/terminvereinbarung.html#/services/10339028/locations/10461

## Aktivizimi

1. Ngarko këta skedarë në GitHub repository.
2. Shko te **Settings → Secrets and variables → Actions → New repository secret**.
3. Shto këto dy secrets:
   - `TELEGRAM_BOT_TOKEN`
   - `TELEGRAM_CHAT_ID`
4. Shko te **Actions → KVR Termin Alarm → Run workflow** për test.

Kujdes: ky projekt vetëm njofton. Nuk rezervon automatikisht.
