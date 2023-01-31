# DiscordBot-RSS-The-Hacker-News
Prosty bot do Discorda napisany w języku Python obsługujący kanał RSS, w tym wypadku [The Hacker News](https://thehackernews.com/).
----
W miejscu "client.run('TOKEN')" należy wpisać TOKEN swojego bota ze strony [Discord Developers](https://discord.com/developers/applications).
 
**WYMAGANIA**:
- Należy zainstalować repozytoria z pliku requirements.txt.

**OBSŁUGIWANE KOMENDY**:
- !rss latest – bot publikuje trzy ostatnie artykuły ze strony 'The Hacker News'
- !rss random – bot publikuje losowy artykuł ze strony 'The Hacker News'
----
Kanał RSS można dowolnie zmodyfikować dodając wybrany przez siebie link do kanału RSS w linijkach:
- feed = feedparser.parse("https://przykladowy.link.com")
