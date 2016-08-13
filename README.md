# 💬 Recon Messenger

This application is a simple Electron wrapper around http://messenger.recon.com. I made it few weeks / months ago. I hope the folks at [Recon](http://recon.com) didn't mind if I share it with you since ... you know ... It's not a big deal and some of you may prefer having a little companion app rather a window browser.

## 📸 Screenshots

![](https://cl.ly/h217/01.png)
![](https://cl.ly/h2rU/02.png)

## 🐛 Known bugs

You spotted a bug not on this list ? Congratulation 🎉 You know can [submit an issue](https://github.com/clawfire/recon-messenger/issues) on the repository following the issues guidelines.

## ❓FAQ

### How is it made ?
I use [Nativefier](https://github.com/jiahaog/nativefier) with the following commande line 
```bash
nativefier --name "Recon Messenger" --icon "~/Downloads/recon.icns" --width 524 --height 695 -f --disable-dev-tools -e 1.1.3 "https://messages.recon.com"
````

Made with ❤️ on a  with [Textmate](https://macromates.com/)