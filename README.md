
[No more support.](https://t.me/sessiztaggersahip)

----

<div align="center">
  <img src="https://s7.gifyu.com/images/indird70e354866f587b4.gif" width="200" height="200">
  <h1>Master UserBot</h1>
</div>
<p align="center">
    Master UserBot, Telegram kullanmanızı kolaylaştıran bir bottur. Tamamen açık kaynaklı ve ücretsizdir.
    <br>
        <a href="https://github.com/quiec/MasterUserBot/blob/master/README.md#kurulum">Kurulum</a> |
        <a href="https://github.com/Quiec/MasterUserBot/wiki/G%C3%BCncelleme">Güncelleme</a> |
        <a href="https://t.me/AsenaUserBot">Telegram Kanalı</a>
    <br>
</p>

----
![Docker Pulls](https://img.shields.io/docker/pulls/fusuf/masteruserbot?style=flat-square) ![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/fusuf/masteruserbot?style=flat-square)

**Android:** Termuxu açın ve bu kodu yapıştırın: `bash <(curl -L https://kutt.it/88I5KA)`

**iOS:** iSH açın ve bu kodu yapıştırın: `apk update && apk add bash && apk add curl && curl -L -o asena_installer.sh https://t.ly/vATX && chmod +x asena_installer.sh && bash asena_installer.sh`

**Windows 10:** [Python](https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l#activetab=pivot:overviewtab) indirin ardından PowerShell bu kodu yapıştırın: `Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://kutt.it/aYTzCm')`

### Basit Yöntem
Eğer botu kurma hakkında fikriniz yoksa burayı okuyunuz: [Kurulum Rehberi](https://github.com/Quiec/MasterUserBot/wiki/Kurulum/)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Quiec/MasterUserBot)
### Zor Yöntem
```python
git clone https://github.com/Quiec/Masteruserbot.git
cd MasterUserBot
pip install -r requirements.txt
# Config.env oluşturun ve düzenleyin. #
python3 main.py
```

## Örnek Plugin
```python
from userbot.events import register
from userbot.cmdhelp import CmdHelp # <-- Bunu ekleyin.

@register(outgoing=True, pattern="^.deneme")
async def deneme(event):
    await event.edit('Gerçekten deneme!')

Help = CmdHelp('deneme') # Bilgi ekleyeceğiz diyoruz.
Help.add_command('deneme', # Komut
    None, # Komut parametresi varsa yazın yoksa None yazın
    'Gerçekten deneme yapıyor!', # Komut açıklaması
    'deneme' # Örnek kullanım.
    )
Help.add_info('@sessiztaggersahip tarafından yapılmıştır.') # Bilgi ekleyebilirsiniz.
# Ya da uyarı --> Help.add_warning('KULLANMA!')
Help.add() # Ve Ekleyelim.
```

## Bilgilendirme
Herhangi bir istek & şikâyet & öneri varsa [destek grubuna](https://t.me/MasterUserBot) ulaşabilirsiniz.

```
    Userbottan dolayı; Telegram hesabınız yasaklanabilir.
    Bu bir açık kaynaklı projedir, yaptığınız her işlemden kendiniz sorumlusunuz. Kesinlikle Asena yöneticileri sorumluluk kabul etmemektedir.
    Asenayı kurarak bu sorumlulukları kabul etmiş sayılırsınız.
```

## Credit

