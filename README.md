# Discord User Banner
Discord kullanıcı bannerı alma kodu.Çalışıyor.

Kodu kendi handlerınıza göre ayarlarsınız. 

```javascript
 let uid = args[0];
```
kısmını eğer message.mentions.members.first() || message.guild.members.cache.get(args[0]) yaparsanız çalışmıyor.
En azından bende çalışmadı..

