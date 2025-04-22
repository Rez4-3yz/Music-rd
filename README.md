![thum](https://github.com/user-attachments/assets/bde82fd4-080b-4645-b56b-3539aeba5cd5)

<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px">Hi, I am Rza 2005 👨‍💻 🌌 [ ( Music untuk Botz RiLis 27 Desember 2024 )
<p align="center">
  <img src="https://files.catbox.moe/6dqscp.jpg" />
</p>

 ## 🌌 [ ( RiLis 27 Desember 2024 ) Name Rza 2005 ]

 ## 🎧 [ 65 Music Di Perbarui jadi 130 Music ( Selasa, 25 Maret 2025 )]

 ## ///=== Music Old dan New Campuran ===/// WhatsApp

 ## ```Versi Case```
```
///=== Music Old dan New Campuran ===///
/// 65 Music di Perbarui Jadi 130 Music

case 'music1':
case 'music2':
case 'music3':
case 'music4':
case 'music5':
case 'music6':
case 'music7':
case 'music8':
case 'music9':
case 'music10':
case 'music11':
case 'music12':
case 'music13':
case 'music14':
case 'music15':
case 'music16':
case 'music17':
case 'music18':
case 'music19':
case 'music20':
case 'music21':
case 'music22':
case 'music23':
case 'music24':
case 'music25':
case 'music26':
case 'music27':
case 'music28':
case 'music29':
case 'music30':
case 'music31':
case 'music32':
case 'music33':
case 'music34':
case 'music35':
case 'music36':
case 'music37':
case 'music38':
case 'music39':
case 'music40':
case 'music41':
case 'music42':
case 'music43':
case 'music44':
case 'music45':
case 'music46':
case 'music47':
case 'music48':
case 'music49':
case 'music50':
case 'music51':
case 'music52':
case 'music53':
case 'music54':
case 'music55':
case 'music56':
case 'music57':
case 'music58':
case 'music59':
case 'music60':
case 'music61':
case 'music62':
case 'music63':
case 'music64':
case 'music65':
case 'music66':
case 'music67':
case 'music68':
case 'music69':
case 'music70':
case 'music71':
case 'music72':
case 'music73':
case 'music74':
case 'music75':
case 'music76':
case 'music77':
case 'music78':
case 'music79':
case 'music80':
case 'music81':
case 'music82':
case 'music83':
case 'music84':
case 'music85':
case 'music86':
case 'music87':
case 'music88':
case 'music89':
case 'music90':
case 'music91':
case 'music92':
case 'music93':
case 'music94':
case 'music95':
case 'music96':
case 'music97':
case 'music98':
case 'music99':
case 'music100':
case 'music101':
case 'music102':
case 'music103':
case 'music104':
case 'music105':
case 'music106':
case 'music107':
case 'music109':
case 'music110':
case 'music111':
case 'music112':
case 'music113':
case 'music114':
case 'music115':
case 'music116':
case 'music117':
case 'music118':
case 'music119':
case 'music120':
case 'music121':
case 'music122':
case 'music123':
case 'music124':
case 'music125':
case 'music126':
case 'music127':
case 'music128':
case 'music129':
case 'music130':
Botzwa.sendMessage(from, { react: { text: "🎧", key: m.key }})
Rza2005_dev = await getBuffer(`https://raw.githubusercontent.com/Rez4-3yz/Music-rd/master/music/${command}.mp3`)
await Botzwa.sendMessage(m.chat, { audio: Rza2005_dev, mimetype: 'audio/mp4', ptt: true }, { quoted: m })
break
```
## ```Versi Plugins```

```
import fetch from 'node-fetch';

const handler = async (m, { conn, command }) => {
    try {
        if (!m || !m.chat) throw new Error();
        if (!conn) throw new Error();

        m.reply(global.wait);

        let audio = `https://raw.githubusercontent.com/Rez4-3yz/Music-rd/master/music/${command}.mp3`;

        await conn.sendMessage(m.chat, { 
            audio: { url: audio }, 
            mimetype: 'audio/mp4', 
            ptt: false, 
            contextInfo: {
                externalAdReply: {
                    showAdAttribution: true,
                    mediaUrl: 'https://instagram.com/name',
                    mediaType: 2,
                    description: '',
                    title: "BOTZ WHATSAPP",
                    body: `${command}`,
                    sourceUrl: ''
                }
            }
        });
    } catch (err) {
        m.reply('Terjadi kesalahan saat mengirim audio. coba lagi nanti.');
    }
};

handler.help = Array.from({ length: 130 }, (_, i) => `music${i + 1}`);
handler.tags = ['audio'];
handler.command = new RegExp(`^(${handler.help.join('|')})$`, 'i');
handler.owner = false;

export default handler;
```
