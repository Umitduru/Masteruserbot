
[No more support.](https://t.me/Mastersuportt/826)

----

<div align="center">
  <img src="https://i.imgyukle.com/2020/05/29/yBpJsP.jpg" width="200" height="200">
  <h1>Asena UserBot</h1>
</div>
<p align="center">
    Asena UserBot, Telegram kullanmanızı kolaylaştıran bir bottur. Tamamen açık kaynaklı ve ücretsizdir.
    <br>
        <a href="https://github.com/quiec/Umitduru/blob/Masteruserbot/README.md#kurulum">Kurulum</a> |
        <a href="https://github.com/Quiec/masteruserbot/wiki/G%C3%BCncelleme">Güncelleme</a> |
        <a href="https://t.me/Masteruserbot">Telegram Kanalı</a>
    <br>
</p>

----

**Android:** Termuxu açın ve bu kodu yapıştırın: `bash <(curl -L https://kutt.it/88I5KA)`

**iOS:** iSH açın ve bu kodu yapıştırın: `apk update && apk add bash && apk add curl && curl -L -o asena_installer.sh https://t.ly/vATX && chmod +x asena_installer.sh && bash asena_installer.sh`

**Windows 10:** [Python](https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l#activetab=pivot:overviewtab) indirin ardından PowerShell bu kodu yapıştırın: `Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://kutt.it/aYTzCx')`

### Basit Yöntem
Eğer botu kurma hakkında fikriniz yoksa burayı okuyunuz: [Kurulum Rehberi](https://github.com/Quiec/Mastersuportt/wiki/Kurulum/)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Quiec/Masteruserbot)
### Zor Yöntem
```python
git clone https://github.com/Quiec/Masteruserbot.git
cd masteruserbot
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
Herhangi bir istek & şikâyet & öneri varsa [destek grubuna](https://t.me/MasterSupport) ulaşabilirsiniz.

```
    Userbottan dolayı; Telegram hesabınız yasaklanabilir.
    Bu bir açık kaynaklı projedir, yaptığınız her işlemden kendiniz sorumlusunuz. Kesinlikle Master yöneticileri sorumluluk kabul etmemektedir.
    Master kurarak bu sorumlulukları kabul etmiş sayılırsınız.
```

## Credit
Thanks for;

