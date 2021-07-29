# Discord User Banner
Discord kullanıcı bannerı alma kodu.Çalışıyor.

Kodu kendi handlerınıza göre ayarlarsınız. 

```javascript
 let uid = args[0];
```
kısmını eğer message.mentions.members.first() || message.guild.members.cache.get(args[0]) yapmayı deneyebilirsiniz.
Bende çalışmadı..

## Code to get Discord user banner. It works.

You set the code according to your own handler.

```javascript
 let uid = args[0];
```
part if message.mentions.members.first() || You could try doing message.guild.members.cache.get(args[0]) .
It didn't work for me..
