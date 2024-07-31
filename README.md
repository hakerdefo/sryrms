# SryRMS

`SryRMS` helps you in installing some popular proprietary as well as libre applications not available in the official repositories of Ubuntu. Currently, `SryRMS` helps you in installing following applications in the good ole `deb` packaging format. All of these applications are sourced from their original upstream projects and not from third parties or from some random folks on the internet.  

 - Brave browser  
 - Chrome browser  
 - Edge browser
 - Firefox browser (deb)
 - Firefox - Beta (deb)
 - Firefox - Developer (deb)
 - Firefox - Nightly (deb)
 - Opera browser  
 - Vivaldi browser  
 - Spotify  
 - Visual Studio Code  
 - Element  
 - Jami  
 - Signal  
 - Skype  
 - Microsoft Teams  
 - ONLYOFFICE  
 - Flatpak  
 
### Dependencies :

`SryRMS` doesn't have any fancy requirements and should work out-of-the-box on all recent versions of Ubuntu. `SryRMS` only requires `Wget` and `GnuPG` to work and these two are already installed by default on almost all Ubuntu installations. Though `SryRMS` has only been tested on Ubuntu, it should work fine on recent versions of Debian.     

### Installation :

Installation of `SryRMS` is very simple. Download **[sryrms-main]** zip, extract its contents and copy the file **sryrms** to **/usr/local/bin/** directory,  

```sh
sudo cp sryrms /usr/local/bin/
```
And make it executable,
```sh
sudo chmod 755 /usr/local/bin/sryrms
```

### Usage :

Open terminal & run,  

```sh
sudo sryrms
```  

And follow the simple interactive menu of `SryRMS` to install your desired applications.  

### Support :

If you liked `SryRMS`, please consider supporting it, even the smallest contribution goes a long way. It is quick & easy via PayPal, Buy Me a Coffee, Liberapay or Stripe:  

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://paypal.me/hakerdefo)  

[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/hakerdefo)  

[![Support via Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/hakerdefo/donate)  

### FAQ :

#### What is the story behind the wonky script name? What on earth does SryRMS mean?  
Sadly, I can't reveal the origin of the name `SryRMS` as I'm bound by the oath of the church of Emacs and if I were to spill the beans, the editor of the beast will come after me, so...  

#### Why Flatpak? Isn't it available in official Ubuntu repositories?  
Yes, it is, but `SryRMS` installs `flatpak` in a way that nicely integrates Flatpak packages with GNOME Software Center and KDE Discover. `SryRMS` also enables the all important Flathub repository while installing `flatpak`.  

#### Will you include my favorite applications X, Y & Z in SryRMS?  
If the upstream developer(s) have a Debian repository and the released version(s) are compatible with current Ubuntu and Debian systems, then yes, I'll for sure include it in `SryRMS`. Please [create a pull request](https://github.com/hakerdefo/sryrms/pulls) and I'll take it from there.    

### License :

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">SryRMS</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/sryrms)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.github.io), is free of known copyright restrictions.  

[sryrms-main]:https://github.com/hakerdefo/sryrms/archive/refs/heads/main.zip  
