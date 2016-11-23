##General Notes

Ubuntu လမ္းညႊန္သည္ ပုဂၢလိကဆိုင္ရာကုမၸၸဏီႏွင့္ေသာ္လည္းေကာင္း အျခားစီးပြားေရး လုပ္ငန္းႀကီးမ်ားႏွင့္ေသာ္လည္းေကာင္း စီးပြားေရးအရသက္ဆိုင္မႈမရွိပါ။
Ubuntu သည္ သံုးစြဲသူမ်ားကို Menu ရုပ္ပံုအသံုးခ် Graphical User Interface  (GUI) ႏွင့္ေသာ္လည္းေကာင္း စာသားအသံုးခ် command line ဆိုင္ရာ text-based command-line interface (CLI) ေသာ္လည္းေကာင္း အလုပ္မ်ားကို လုပ္ေဆာင္ႏိုင္ေစပါတယ္။ Ubuntu တြင္(command-line-interface)ကို `Terminal` လို႕ေခၚပါတယ္။ Terminal ကိုစဖြင့္မယ္ဆိုရင္ `Menu- Applications-Accessories -Terminal` စသည္ျဖင္႔ အဆင့္တိုင္းသြားေရာက္ႏိုင္ပါသည္။ Terminal တြင္ ခဲေရာင္မ်ဥ္းအစက္မ်ားအတြင္း စာသားမ်ားကို ထည့္သြင္းအသံုးျပဳႏိုင္ပါသည္။

ကြန္ပ်ဴတာလုပ္ေဆာင္မႈစနစ္မွ ေျပာင္းလဲခ်က္မ်ားကို ေျပာင္းလဲခြင့္ရွိသူ (Admin အခြင့္ရွိတဲ့) အသံုးျပဳသူကပဲေဆာင္ရြက္ႏိုင္ပါသည္။ `sudo` Command က အသံုးျပဳသူကို ေျပာင္းလဲခြင့္ရွိသူ Admin အျဖစ္ ယာယီသတ္မွတ္ေပးသည္(ဥပမာ - ပရိုဂရမ္တစ္ခု သြင္းစဥ္ (သို႕) စနစ္ပိုင္းဆိုင္ရာေျပာင္းလဲစဥ္)။ နမူနာအေနျဖင့္ ေအာက္တြင္ေဖာ္ၿပထားသည္။

	sudo bash

`gksudo` ကို Graphical Application ေတြဖြင့္ရာမွာ `sudo` အစား Run Command မွေသာ္လည္းေကာင္း မီႏူးမ်ားမွေသာ္လည္းေကာင္း အသံုးျပဳႏိုင္ပါတယ္။နမူနာ အေနျဖင့္ ေအာက္တြင္ေဖာ္ၿပထားသည္။

	gksudo gedit /etc/apt/sources.list

ဖိုင္အမ်ားစုရဲ႕ ခန္႕ခြဲမႈေတြကို ရင္းျမစ္ျပင္ဆင္ခြင့္ရွိတဲ့ Admin  အခြင့္ (root Administrative privileges)ႏွင့္ Nautilus file မန္ေနဂ်ာကဲ့သို႕ အသံုးျပဳကာနဲ႕ ေဆာင္ရြက္ႏိုင္ပါသည္။ Menu မွတဆင့္ အသံုးျပဳမယ္ဆိုရင္ `gksudo` ကိုအသံုးျပဳပါ။

	gksudo nautilus (သို႕မဟုတ္) sudo nautilus

`man` ကေတာ့ ကြန္မန္းေတြအတြက္ အကူအညီလိုလာၿပီဆိုရင္ အသံုးျပဳႏိုင္ပါတယ္။နမူနာအေနနဲ႕ `man sudo` လို႕ရိုက္ထည့္လိုက္မယ္ဆိုရင္ `sudo` ကြန္မန္းနဲ႕ဆိုင္တဲ့
လက္စြဲဖိုင္စာမ်က္ႏွာေတြကိုျမင္ေတြ႕ရမွာျဖစ္ပါသည္။ 

	man sudo

`apt-get`  ႏွင့္ `aptitude` ေတြကို ပရိုဂရမ္ေတြ ပက္ေက့ (package) ေတြ ထည့္သြင္းရာမွာအျမန္ဆံုးနည္းအေနနဲ႕ အသံုးျပဳပါတယ္။ GUI ထည့္သြင္းမႈအတြက္ Synaptic Package Manager ကိုလဲအသံုးျပဳႏိုင္ပါတယ္။ ဒါေပမယ့္ ပရိုဂရမ္ေတြ ပက္ေက့ (package) အမ်ားစုဟာ `apt-get install` ႏွင့္ေရာ Synaptic Package Manager ႏွင့္ပါ ထည့္သြင္းႏိုင္ပါသည္။အခုလမ္းညႊန္မွာ ျမင္ေတြ႕ႏိုင္ပါသည္။

	sudo apt-get install package 

Synaptic မွာပက္ေက့ေတြ (package) ကိုရွာေဖြပံုနဲ႕ ထည့္သြင္းပံုက ဤသို႕ျဖစ္ပါသည္။ အမိန္႕ေပးမႈအမ်ားအျပားကို nano စာသား အယ္ဒီတာ အသံုးျပဳခိုင္းေစပါတယ္။ နာႏိုက
Linux တိုင္းမွာ ရရွိတဲ့ အယ္ဒီတာျဖစ္ပါသည္။ တစ္ခါတရံမွာ Ubuntu မွာပါတဲ့ gedit ထက္အသံုးျပဳရတာပိုလြယ္ပါတယ္။

Menu ဆိုတာကေတာ့ desktop အေပၚဘက္မွာရွိ မီႏူးဘားကို ရည္ညႊန္းပါတယ္။ မိုက္ခရိုေဆာ့ဖ္ဝင္းဒိုးမွာရွိတဲ့ Start menu၊ Apple Macintosh မွာရွိတဲ့ Menu bar ေတြနဲ႕တူတူပါပဲ။

တကယ္လို႕ ၆၄ ဘစ္ ဗားရွင္းစနစ္ကို အသံုးျပဳမယ္ဆိုရင္ i386 ကို amd64 နဲ႕ အစားထိုးရမွာ ျဖစ္ပါသည္။

###Other Versions

လက္ရွိအသံုးျပဳေနတဲ့ Ubuntu version ကိုၾကည့္ခ်င္ရင္ Terminal ေပၚမွာ ေအာက္ပါအတိုင္းရိုက္ထည့္ၿပီး Enter ႏွိပ္ပါ။

	lsb_release -a

လက္ရွိအသံုးျပဳေနတဲ့ kernel ကိုၾကည့္ခ်င္ရင္ရင္ေတာ့ Terminal မွာ ေအာက္ပါအတိုင္းရိုက္ထည့္ၿပီး Enter ႏွိပ္ပါ။

	uname -a

###Newer Versions  of Ubuntu 

Ubuntu ကို ၆လလွ်င္တစ္ႀကိမ္ထုတ္ေဝၿပီး ႏွစ္စဥ္ ဧၿပီလႏွင့္ေအာက္တိုဘာလတို႕တြင္ ထုတ္ေဝပါသည္။ Trusty Tahr (14.04) (http://ubuntuguide.org/wiki/Ubuntu_Trusty), မ်ားမႀကာမီ ေနာက္ဆံုးထြက္ Yakkety Yak ကို ၂၀၁၆ခုႏွစ္ ေအာက္တိုဘာလတြင္ အခမဲ့ ရယူႏိုင္မည္ျဖစ္ပါသည္။သို႕ရာတြင္ ၄င္းသည္ ကာလရွည္ႀကာ ေထာက္ပံ့မႈေပးသည့္ LTS Version မဟုတ္ပါ။

###Older Versions of Ubuntu

https://wiki.ubuntu.com/Releases

###Other Resources 

Ubuntu Forums (http://ubuntuforums.org/) တြင္ အြန္လိုင္းေျဖရွင္းခ်က္မ်ားႏွင့္ အျခားေသာအေသးစိတ္အခ်က္အလက္မ်ားကို ကူညီေပးရန္ အဖြဲ႕အစည္းမ်ားစြာ ရွိပါသည္။
ျပည္တြင္း အဖြဲ႕အစည္းအေနျဖင့္ Ubuntu for Myanmar (ubuntu-mm) (http://ubuntu-mm.net/) ရွိၿပီး ျမန္မာဘာသာျဖင့္ Ubuntu အေႀကာင္းေလ့လာႏိုင္ပါမည္။

- [ubuntu-mm.net](http://ubuntu-mm.net)
- [ask.ubuntu.com](http://ask.ubuntu.com)
- [FB Ubuntu-MM Group](http://fb.com/groups/ubuntu4mm)
- [FB Pages](http://fb.com/ubuntumm)
- [Ubuntu Myanmar LoCo Team](http://wiki.ubuntu.com/MyanmarTeam)
- [Ubuntu-MM LoCo](http://loco.ubuntu.com/teams/ubuntu-mm)

-------------------

##Ubuntu Resources 

###Unity Desktop

[Unity](http://en.wikipedia.org/wiki/Unity_%28desktop_environment%29) ဆိုသည္မွာ Ubuntu တြင္ အသံုးျပဳသည့္ နဂိုမူလပါေသာ Desktop ပံုစံျဖစ္ပါသည္။ (Gnome) ဂႏုမ္းမွ အသံုးျပဳသည့္ GTK ပလက္ေဖာင္းျဖင့္ အဆင္ေျပသင့္ေတာ္ပါသည္။ netbook မ်ားတြင္ အသံုးျပဳရန္ ဒီဇိုင္းျပဳလုပ္ထားေသာ္လည္း အျခားေသာ စက္ပစၥည္းအမ်ိဳးအစားမ်ားတြင္ပါ အသံုး၀င္ေစရန္ canonical မွ ျပင္ဆင္ေပးထားပါသည္။

###Gnome Project 

[Gnome 3](http://www.gnome.org/) သည္ Ubuntu အတြက္ ပံုစံအသစ္အေနျဖင့္ ရယူႏိုင္ပါသည္။ Gnome လုပ္ငန္းစဥ္မ်ား (http://projects.gnome.org/) ႀကည့္႐ႈ ရယူႏိုင္ပါသည္။

###Installation ျပဳလုပ္ပံု  - ၁ [(link)](https://launchpad.net/~gnome3-team/+archive/gnome3) 

	sudo add-apt-repository ppa:gnome3-team/gnome3   
	sudo apt-get update   
	sudo apt-get dist-upgrade   
	sudo apt-get install gnome-shell   

###installation ျပဳလုပ္ပံု  - ၂ [(link)](https://launchpad.net/~ubuntugnometeam)

	sudo add-apt-repository ppa:ubuntugonmeteam/gnome3   
	sudo add-apt-repository ppa:ubuntugonmeteam/ppa-gen   
	sudo apt-get update   
	sudo apt-get install ugr-desktop-g3   
	sudo apt-get dist-upgrade   

###Ubuntu Screenshots 

- [What is Ubuntu?](http://www.ubuntu.com/ubuntu)    
- [Ubuntu 11.04 Unity Desktop](http://www.youtube.com/watch/v=HMztaKt_1_E)    
- [Other YouTube videos](https://www.youtube.com/results?search_query=ubuntu+11.04)   
မႀကာမီ ျမန္မာဘာသာ သင္ႀကားပို႕ခ်ခ်က္မ်ား ထည့္သြင္းမည္။

###News Application Resources 

[GetDeb](http://www.getdeb.net) ေနာက္ဆံုးထြက္ရွိေသာ software မ်ားကိုတရားဝင္ ထိန္းသိမ္းထားရာ ေနရာမ်ားကဲ့သို႕ ရရွိႏိုင္ျခင္း (သို႕) မရရွိႏိုင္ျခင္း အတူတူျဖစ္သည္။ `.deb` ဖိုင္ပံုစံျဖင့္ထည့္သြင္းရန္ လြယ္ကူပါသည္။ (ဤေနရာတြင္ ဆက္လက္ေလ့လာပါ။ Apt and Package Basics).
   
- [Top 100 Open source Applications](http://ubuntulinuxhelp.com/top-100-of-the-best-useful-opensource-applications/)
- [Linux Alternatives](http://www.linuxalt.com/)   
See our full list of add-on applications.

###Other *buntu guides and help manuals

- [Kubuntu](http://www.kubuntuguide.info) သည္ နာမည္ေက်ာ္ႀကားေသာ KDE desktop ကို အသံုးျပဳထားပါသည္။
- [Xubuntu](http://www.xubuntuguide.org) can run with as little as 256 Mb RAM.It is better for older machines with limited resources.---
- [Lubuntu](https://wiki.ubuntu.com/Lubuntu) သည္ RAM 256Mb ႏွင့္ပင္ အသံုးျပဳႏိုင္ပါသည္။ အိုေဟာင္းေနေသာ စက္မ်ားႏွင့္ပင္ သင့္ေတာ္ပါသည္။
- [Offical Ubuntu Server Guide](https://help.ubuntu.com/10.04/serverguide/C/index.html) Ubuntu server လမ္းညႊန္ - server packages မ်ားအတြက္ ေကာင္းမြန္ေသာ ကိုးကားမႈျဖစ္ပါသည္။
- [Ubuntu Doctors Guide](http://www.ubuntudoctorsguild.org/) က်န္းမာေရးႏွင့္သက္ဆိုင္ေသာ ေနရာမ်ားတြင္သံုးေသာ (K)ubuntu Linux မ်ားအတြက္
စုစည္းထားေသာ လမ္းညႊန္ခ်က္မ်ား
- [SkoleLinux](http://www.slx.no/en/take-a-tour) -- Debian/Ubuntu Linux (open-source) မ်ားအတြက္ ပညာရပ္ဆိုင္ရာမ်ား စုစည္းထားမႈ

--------------------- 

##Installing Ubuntu

###Ubuntu ထည့္သြင္းအသံုးျပဳႏိုင္ရန္ Hardware လိုအပ္ခ်က္မ်ား

Ubuntu Natty Narwhal သည္ 384 Mb ပမာဏသည္ RAM ရွိရံဳမွ်ျဖင့္ ေကာင္းစြာလည္ပတ္ႏိုင္သည္။ (GUI installer ျဖင့္ထည့္သြင္းလွ်င္ အနည္းဆံုး 256 Mb ပမာဏလိုအပ္ၿပီး၊စာသားျဖင့္သာေဖာ္ၿပေသာ installer ကို သံုးလွ်င္ 192 Mb ပမာဏသာလိုအပ္သည္)။ Notebooks မ်ားတြင္ Ubuntu Natty Narwhal ကိုေကာင္းစြာ အသံုးျပဳႏိုင္သည္။

Ubuntu ထည့္သြင္းျခင္းသည္ Harddisk ေနရာလြတ္ 3->4 Gb မွ်သာ အသံုးျပဳၿပီး အဆင္ေျပစြာ အသံုးျပဳႏိုင္ရန္ 8->10Gb သာ လိုအပ္သည္။ အကယ္၍ သင့္ကြန္ပ်ဴတာ၏ memory ပမာဏသည္ ယခုေဖာ္ၿပခဲ့သည္ထက္ နည္းပါးေနပါက အျခားေသာ
ဆင္တူ OS မ်ားျဖစ္ေသာ ေအာက္ပါ OS မ်ားကို အသံုးျပဳႏိုင္သည္။    

- [Lubuntu](https://wiki.ubuntu.com/Lubuntu) (၁၆၀ Mb RAM ပမာဏရွိရံုျဖင့္ အသံုးျပဳႏိုင္သည္။)   
- [PuppyLinux](http://www.puppylinux.org/) (၂၅၆ Mb RAM ပမာဏရွိရံုျဖင့္ အသံုးျပဳႏိုင္သည္။)   
(သို႕မဟုတ္) 
- DSL
(http://damnsmallinux.org) (အနည္းဆံုး RAM ပမာဏ၊Harddisk ေနရာလြတ္ အနည္းငယ္သာရွိရံု၊ USB drive မွ အသံုးျပဳရန္၊ သို႕မဟုတ္ အျခား Operation System မ်ား အတြင္းမွ softwareတစ္ခုကဲ့သို႕အသံုးျပဳရန္)။

###Fresh Installation

####Ubuntu တစ္ခုတည္း သီးသန္႕ထည့္သြင္းျခင္း

[ဒီေနရာမွ](http://www.ubuntu.com/download/ubuntu/download) မွ Ubuntu ၏
ေနာက္ဆံုးထြက္ရွိထားေသာ IOS အား download ဆြဲယူပါ။ ထို IOS အား CD ေပၚသို႕ Ubuntu installation CD (LiveCD) အျဖစ္ အသံုးျပဳႏိုင္ရန္ မည္သို႕ျပဳလုပ္ရမည္ကို
[How To](https://help.ubuntu.com/community/BurningIsoHowto) တြင္ လမ္းညႊန္ထားသည္။ ထိုလမ္းညႊန္ခ်က္အတိုင္း ျပဳလုပ္ထားသည့္ Live CD ကို Ubuntu ထည့္သြင္းရန္အတြက္ အသံုးျပဳသည္။

အျခားနည္းလမ္းတစ္ခုအေနျဖင့္ Server version ကို အရင္ထည့္သြင္းၿပီးမွ Ubuntu desktop version ကို ထည့္သြင္း၍ အသံုးျပဳႏိုင္သည္။

Server version ကဲ့သို႕ ပိုမိုျမန္ဆန္သည့္ စာသားျဖင့္သာေဖာ္ၿပေသာ installer ကို အသံုးျပဳထားသည့္ ISO file ကို [Alternative Download](http://www.ubuntu.com/download/ubuntu/alternative-download) တြင္ ရယူႏိုင္သည္။ ထို ISO တြင္Desktop CD(Regular Download) ထက္ေရြးခ်ယ္ႏိုင္ေသာ installation လုပ္ငန္းစဥ္မ်ား ပိုမိုပါ၀င္သည္။

LiveCD ကို USB flashdrive ေပၚသို႕ (usb-creater-gtk) အသံုးျပဳ၍ ထည့္သြင္းၿပီး ထို flashdrive ကို CD drive မပါဝင္သည့္ ကြန္ပ်ဴတာမ်ားေပၚတြင္ Ubuntu ထည့္သြင္းရန္ အသံုးျပဳႏိုင္သည္။ [ဒီေနရာတြင္ၾကည့္ပါ။](https://help.ubuntu.com/community/Installation/FromUSBStick)

####Windows ႏွင့္ Ubuntu ကို ကြန္ပ်ဴတာတစ္လံုးထဲေပၚတြင္ ယွဥ္တြဲတင္ျခင္း

ကြန္ပ်ဴတာတစ္လံုးထဲေပၚတြင္ Windows ႏွင့္ Ubuntu ယွဥ္တြဲတင္ရာတြင္ အခက္အခဲမ်ား ႀကံဳေတြ႕ရႏိုင္ပါသည္။ Windows ၏ bootloader သည္ Windows သီးသန္႕ကိုသာ ေထာက္ပံ့သည့္အတြက္ ကြန္ပ်ဴတာေပၚတြင္ Windows ကို ဦးစြာထည့္သြင္းရပါမည္။ ပံုမွန္ Windows ထည့္သြင္းသည့္လုပ္ငန္းစဥ္တြင္ Hard drive ၏
ေနရာရွိသမွ်ကို အသံုးျပဳသည့္အတြက္ Ubuntu ထည့္သြင္းရန္ ေနရာလြတ္ရရွိရန္ဆိုပါက Windows မွအသံုးျပဳထားသည့္ Hard drive ကိုခ်ံဳ႕ေပးရန္ လိုအပ္ပါသည္။(Hard drive ပမာဏကိုမေျပာင္းလဲခင္ ဦးစြာမလိုအပ္ေသာ ဖိုင္မ်ားကို ရွင္းလင္း၍ ဖိုင္ျပန္စီေသာ လုပ္ငန္းစဥ္ကို လုပ္ေဆာင္ထားပါ။)

Windows ၏ Hard drive partition ကိုခ်ံဳ႕ၿပီးပါက  Ubuntu ကို ထည့္သြင္းရန္သို႕မဟုတ္ Hard disk 
partition မ်ားကို ထပ္မံျပဳျပင္ေျပာင္းလဲႏိုင္ရန္အတြက္ ကြန္ပ်ဴတာကို reboot ျပန္လုပ္ေပးရပါမည္။
ဤသို႕ျပဳလုပ္ျခင္းအားျဖင့္ Windows စနစ္မွ အသစ္ျပဳျပင္လုပ္ေဆာင္ထားေသာ    Hard drive ကို သိရွိေစၿပီး (Windows XP တြင္ `chkdsk` ကိုအသံုးျပဳၿပီး ေနာက္ပိုင္းထြက္ရွိလာေသာ Windows စနစ္မ်ားတြင္ အျခားေသာ Hard drive ကိုစစ္ေဆးသည့္ utilities မ်ားကို အသံုးျပဳသည္။)ထို႕အျပင္ bootup ဖိုင္မ်ားကို ေျပာင္းလဲေရးသားေစသည္။ (ထိုကဲ့သို႕ reboot မျပဳလုပ္ခဲ့ပါက Windows အသံုးျပဳေသာ Hard drive partition ၏ bootup ဖိုင္မ်ားကို Windows Recovery Console အသံုးျပဳ၍ ကိုယ္တိုင္ ျပင္ဆင္ေပးရမည္ျဖစ္သည္။

Windows စနစ္ထည့္သြင္းျခင္းနည္းသစ္မ်ားတြင္ Hard drive primary partition ၂ခုအသံုးျပဳသည္
(Windows စနစ္စတင္ရန partition  အေသး၁ခုႏွင့္ Windows စနစ္တစ္ခုလံုးအတြက္ partition အႀကီးတစ္ခု)။ Ubuntu Linux စနစ္ထည့္သြင္းရာတြင္လည္း Hard drive partition ၂ခုလိုအပ္ပါသည္ (`linux-swap` partitionႏွင့္ စနစ္တစ္ခုလံုးအတြက္ partition)။ Linux အတြက္ Hard drive partition မ်ားခြဲရာတြင္ primary partition သို႕မဟုတ္ primary partition ေပၚမွ ျပန္ခြဲေ၀ထားေသာ logical partition  ၂ခု အသံုးျပဳရမည္။အခ်ိဳ႕ကြန္ပ်ဴတာေရာင္းခ်သူမ်ားသည္ Hard drive ၏ primary partition ၄ခုလံုးကို အသံုးျပဳထားတတ္သည့္အတြက္ Ubuntu  ထည့္သြင္းရန္အတြက္ partition ေနရာလြတ္မရွိေႀကာင္း ေဖာ္ျပေနတတ္သည္။ Hard drive ၏ primary partition ၁ခုရွိလွ်င္ ထို primary partition  ေပၚတြင္ logical partition မ်ားထပ္မံခြဲ၍ Ubuntu  ကိုထည့္သြင္းႏိုင္သည္။(Ubuntu အတြက္ primary  partition ျဖစ္ေစ logical partition ျဖစ္ေစ အသံုးျပဳႏိုင္သည္။)

အကယ္၍ Hard drive ေပၚတြင္ primary partition ၂ခုသာရွိပါက(ထို၂ခုတြင္ ေနရာလြတ္မ်ားစြာရွိေနလွ်င္) Ubuntu ကို ဒုတိယ operation system အျဖစ္ထည့္သြင္းရာတြင္ အခက္အခဲရွိမည္မဟုတ္ပါ။ Ubuntu LiveCD ကို `largest available free space` တြင္ ထည့္သြင္းရန္ခြင့္ျပဳလိုက္ရံုျဖင့္ အလိုအေလွ်ာက္ ျပဳလုပ္သြားႏိုင္သည္။ အျခား Partition ၁ခုတြင္ ေနရာလြတ္ အမ်ားအျပားရွိေနပါက Ubuntu LiveCD သည္ Ubuntu ကို `largest available free space` တြင္ ထည့္သြင္းေပးလိမ့္မည္ျဖစ္သည္။

မူလ Windows စနစ္၏ partition သည္ အနည္းဆံုး 20GB  (Vista ႏွင့္ Windows 7 ဆိုလွ်င္ 30GB)
ရွိရမည္ျဖစ္ၿပီး Ubuntu အတြက္ partition သည္ အနည္းဆံုး 10G (20GB ေပးႏိုင္ရင္ပိုေကာင္းပါသည္။) ရွိရမည္ျဖစ္သည္။သင့္တြင္ Hard drive  ေနရာလြတ္မ်ားစြာရွိေနလွ်င္ သင္ႀကိဳက္သည့္ operation system ကို ေနရာႀကိဳက္သေလာက္ ပိုေပးႏိုင္ပါသည္။

အျပန္အလွန္အားျဖင့္ သင့္ကြန္ပ်ဴတာတြင္ Ubuntu ကို အရင္ထည့္သြင္းၿပီးမွ GParted ျဖင့္ primary `NTFS` partition တစ္ခု ဖန္တီး၍ Windows စနစ္ကို ထည့္သြင္းႏိုင္ပါသည္။ (GParted ကို LiveCD/USB တစ္ခုမွေန၍ အသံုးျပဳ၇ပါမည္။) ထို primary NTFS partition ကိုဖန္တီးၿပီးပါက သင္၏ Windows CD/DVD မွ boot လုပ္၍ Windows စနစ္ကိုထို NTFS partition တြင္ထည့္သြင္းရန္ ေရြးခ်ယ္ရမည္။ထည့္သြင္းျခင္း လုပ္ငန္းစဥ္ ၿပီးဆံုးပါက ကြန္ပ်ဴတာပံုမွန္ အလုပ္လုပ္ေဆာင္ႏိုင္ေစရန္ reboot ျပန္လုပ္ပါ။ထိုလုပ္ငန္းစဥ္အားလံုး ၿပီးဆံုးသြားလွ်င္ Ubuntu LiveCD/USB ကိုသံုး၍ `GRUB` ကို `MBR` တြင္ျပန္လည္ထည့္သြင္းပါ။ (အဘယ္ေႀကာင့္ဆိုေသာ္ Windows သည္ `MBR` ကိုျပဳျပင္၍ သူ၏ကိုယ္ပိုင္ bootloader ကို master bootloader အျဖစ္ေျပာင္းလဲသြား၍ျဖစ္ပါသည္။) `GRUB` ကိုထည့္သြင္းၿပီးပါက သင္ႏွစ္သက္ရာ OS ျဖင့္ boot
လုပ္ႏိုင္မည္ျဖစ္သည္။

###အျခားေသာ Windows ႏွင့္ Ubuntu ယွဥ္တြဲ ထည့္သြင္းျခင္း နည္းလမ္းမ်ား

[Wubi](http://www.ubuntu.com/getubuntu/download-wubi) (Windows-based Ubuntu
Installer), Ubuntu ကို Windows စနစ္ေပၚတြင္  Hard drive အတုတစ္ခုဖန္တီး၍ အသံုးျပဳႏိုင္ရန္
လုပ္ေဆာင္ေပးေသာ dual-boot installer ၁ခုျဖစ္သည္ (သို႕ေသာ္Ubuntu ၏စြမ္းေဆာင္ရည္
က်ဆင္းႏိုင္ပါသည္။ Windows စနစ္ေပၚတြင္ အသံုးျပဳရသည့္အတြက္ ဤနည္းလမ္းကို Ubuntu ကို
ယာယီ အသံုးျပဳရန္အတြက္သာ သံုးရန္သင့္ေတာ္ပါသည္။ Ubuntu ကိုအျမဲတမ္း အသံုးျပဳမည္ဆိုပါက
သီးသန္႕ partition, သီးသန္ု႕ filesystem ေပၚတြင္ ထည္႕သြင္းျခင္းသာ အေကာင္းဆံုးနည္းလမ္း
ျဖစ္ပါသည္။

[Easy BCD](http://neosmart.net/dl.php?id=1), Windows စနစ္ေပၚတြင္ အသံုးျပဳရသည့္ အခမဲ့
Program တစ္ခုျဖစ္သည္။ Windows 7/Vista ၏ bootloader ကို ျပဳျပင္ေျပာင္းလဲျခင္းျဖင့္ Windows 
7/Vista ႏွင့္ Ubuntu (တျခား operation systems မ်ားအတြက္လည္း အသံုးျပဳႏိုင္သည္။) ကြန္ပ်ဴတာ ၁ လံုးတည္းေပၚတြင္ အသံုးျပဳႏိုင္ေစသည္။

###Installing multiple OS on a single computer

ကြန္ပ်ဴတာတစ္လံုးတည္းေပၚတြင္ Operation System မ်ား ၁ခုထက္ပို၍ အသံုးျပဳျခင္း

>**သတိျပဳရန္** Ubuntu ထည့္သြင္းေသာလုပ္ငန္းစဥ္အတြင္း ေရြးခ်ယ္စရာအဆင့္တစ္ခုရွိပါသည္ (Ready to install > Advanced)။ ၄င္းမွာ GRUBF2 bootloader ကို MBR (Master Boot Record) အားေျပာင္းလဲျခင္းမျပဳလုပ္ပဲ (K)Ubuntu OS ထည့္သြင္းထားေသာ Harddisk Partition အတြင္း ထည့္သြင္းရန္ ေရြးခ်ယ္ျခင္းျဖစ္သည္။ ထိုအဆင့္ကိုလုပ္ေဆာင္ရာတြင္ အထူးသတိျပဳရန္လိုအပ္ေသာအခ်က္မွာ သင္၏ကြန္ပ်ဴတာစနစ္တြင္ boot လုပ္ရန္အတြက္ သီးျခား Harddisk Partition တစ္ခု(သို႕) Operation System ၂ ခုထပ္ပို၍ အသံုးျပဳထားျခင္း (သို႕) chainloads bootloaders မ်ား အသံုးျပဳထားျခင္းရွိမရွိပင္ ျဖစ္သည္။ ထိုသို႕ေသာစနစ္မ်ားတြင္ MBR ကိုျပဳျပင္ေျပာင္းလဲျခင္းမလုပ္သည္မွာ အေကာင္းဆံုးပင္ျဖစ္သည္။
﻿**ဥပမာ** Destop version GUI installer ကိုအသံုးျပဳ၍ installation ျပဳလုပ္ေနစဥ္အတြင္း အဆင့္တစ္ခုတြင္ ေအာက္ပါအတိုင္းေပၚလာမည္ျဖစ္သည္။

	Summary > Advanced > Device for boot loader installation: /dev/sda6

အထက္ပါ ဥပမာတြင္ ထိုအေျခအေနအတိုင္း ထားရွိပါက GRUB2 bootloader သည္ `/dev/sda6` ((K)Ubuntu OS ထည့္သြင္းထားသည့္ Harddisk Partition ) အတြင္းသို႕သာ ေရာက္ရွိသြားမည္ျဖစ္ၿပီး MBR (Master Boot Record) ကိုေျပာင္းလဲမည္မဟုတ္ပါ။သို႕ေသာ္ `/dev/sda` ၏ default setting တြင္ထားရွိလိုက္ပါက GRUB2
သည္ `/dev/sda6` ((K)Ubuntu OS ထည့္သြင္းထားသည့္ Harddisk Partition ) အတြင္းသို႕
ေရာက္ရွိသြားမည္ ျဖစ္သည့္အျပင္ MBR  (Master Boot Record) ကိုလည္း ျပဳျပင္ေျပာင္းလဲသြားပါမည္။ ထိုအခါ GRUB2 သည္ ကြန္ပ်ဴတာေပၚတြင္ ထည့္သြင္းထားသည့္ Operation System  အားလံုး၏ master bootloader အျဖစ္ေျပာင္းလဲသြားမည္ျဖစ္သည္။အျခားေသာ bootloader (GRUB2 မဟုတ္သည့္) မ်ားကို အသံုးျပဳေနသူျဖစ္လွ်င္ ထိုအေျခအေနသည္ အဆင္ေျပမည္မဟုတ္ပါ။

###Start Manager ကို အသံုးျပဳ၍ Grub ၏ setting မ်ားကို ေျပာင္းလဲျခင္း

Grub သည္ (Operation System ၁ခုထပ္ပို၍ ထည့္သြင္းထားေသာ ကြန္ပ်ဴတာမ်ားတြင္) မည္သည့္ OS ကို ပံုမွန္ ဦးစားေပးအေနျဖင့္ စတင္လည္ပတ္ေစမည္ကို သတ္မွတ္ျခင္းႏွင့္ အျခားေသာ bootup setting မ်ားကို ထိန္းခ်ဳပ္သည့္ bootup utility ၁ခုျဖစ္သည္။ [Startup Manager](http://sourceforge.net/projects/startup-manager/) ကို အသံုးျပဳ၍ Grub ၏ setting  မ်ားကို ေျပာင္းလဲႏိုင္သည္။ Startup Manager သည္ Grub (Grub Legacy ), Grub 2, Usplash, and Splashy စသည့္ bootloader မ်ား၏ setting မ်ားကို ကြပ္ကဲရာတြင္ အသံုးျပဳသည့္ software ျဖစ္သည္။ Startup Manager အသံုးျပဳပံုကို [ဒီေနရာ](https://help.ubuntu.com/community/StartUpManager) တြင္ႀကည့္ရွုႏိုင္သည္။ Startup Manager ထည့္သြင္းရန္အတြက္

	sudo apt-get install startupmanager menu

Startup Manager လည္ပတ္ေစရန္

	Menu > System > Administration > Startup Manasger

>**မွတ္ခ်က္** Grub setting မ်ားကို command-line interface မွလည္း ေျပာင္းလဲျပင္ဆင္ႏိုင္သည္။

###Mac OS X ႏွင့္ Ubuntu ကို ကြန္ပ်ဴတာတစ္လံုးတည္းေပၚတြင္ ယွဥ္တြဲတင္ျခင္း

Mac OS X သည္ Linux ႏွင့္ တည္ေဆာက္ပံု ဆင္တူသည္ (Max OS X သည္ BSD Unix ကို
အေျခခံထားျခင္းျဖစ္သည္။) Mac OS X ႏွင့္ Ubuntu ကို ယွဥ္တြဲတင္ျခင္းႏွင့္ ပတ္သတ္ေသာ
အေသးစိတ္လမ္းညႊန္ခ်က္မ်ားကို [ဒီေနရာတြင္](http://help.ubuntu.com/community/MacBook) တြင္ေလ့လာႏိုင္သည္။

####Ubuntu ရွိၿပီးသား ကြန္ပ်ဴတာေပၚတြင္ Mac OS X တင္ျခင္း

Ubuntu ကို Mac OS X ႏွင့္ ယွဥ္တြဲတင္မည္ဆိုပါက Ubuntu ကို ထည့္သြင္းမည့္ Harddisk Partition ကို ext2 ကို ေရြးခ်ယ္ပါ။ (ထိုလုပ္ငန္းစဥ္အတြက္ Super Grub Disk CD သည္ အသံုး၀င္ေသာ utility ျဖစ္သည္။) Super Grub ISO ဖိုင္ကို [ဒီေနရာတြင္](http://supergrub.forjamari.linex.org) တြင္ download ရယူႏိုင္သည္။

Ubuntu ကို ထည့္သြင္းၿပီးပါက Grub start-up list ကို ျပင္ဆင္ေျပာင္းလဲပါ။

	sudo nano /boot/ grub/menu.1st

ထို႕ေနာက္ ေအာက္ပါစာေႀကာင္းမ်ားကို ထပ္ေပါင္းထည့္ပါ။

	title Mac OS X root (hd0,0) makeactive chainloader + 1

ၿပီးလွ်င္ Mac ကို reboot လုပ္၍ Mac OS X  တြင္ပါ၀င္ေသာ Terminal ကို သြားပါ။ (boot လုပ္ရာတြင္
အခက္အခဲရွိပါက Mac OS X DVD ကိုအသံုးျပဳ၍ boot လုပ္ပါ။) F8 ကိုႏွိပ္၍ -s ဟု ရိုက္ထည့္ပါ။ ထို႕ေနာက္ ရိုက္ထည့္ရမည့္စာေႀကာင္းမ်ားမွာ `fdiskn -e /dev/rdisk0 flag 2` (flag 2သည္ ယခုဥပမာ၏ Harddisk Partition number 2 ျဖစ္သည္။ သင္၏ Mac တြင္ အသံုးျပဳထားသည့္ Partition number ေပၚတြင္ လိုက္၍ေျပာင္းလဲႏိုင္သည္။) quity reboot ပံုမွန္အလုပ္ လုပ္ေဆာင္ႏိုင္ၿပီဟု မေသခ်ာေသးပါက Super Grub Disk CD ကို အသံုးျပဳ၍ Grub ကို active 
လုပ္ပါ။

####Mac OS X ရွိၿပီးသား ကြန္ပ်ဴတာေပၚတြင္ Ubuntu တင္ျခင္း

Booth လုပ္ေနစဥ္အတြင္း boothloader တြင္ ပံုမွန္လုပ္ေဆာင္ေနျခင္းမရွိဟု သတင္းပို႕ခ်က္ (ဥပမာ HFS+error) မ်ားေပၚလာပါက Super Grub ကိုအသံုးျပဳ၍ Linux GRUB ႏွင့္ MBR (Master Boot Record) ကို ျပန္လည္ျပင္ဆင္ႏိုင္သည္။ Ubuntu ကို ထည့္သြင္းၿပီးပါက Grub start-up list ကိုျပင္ဆင္ေျပာင္းလဲပါ။

	sudo nano /boot/grub/menu.1st

ထို႕ေနာက္ ထပ္ေပါင္းထည့္ရမည့္ စာေႀကာင္းမ်ားမွာ

	title Mac OS X root (hd0,0) makeactive chainloader +1

အကယ္၍ သင္သည္GRUB တြင္ Mac OS X သို႕မဟုတ္ Windows ႏွင့္ပတ္သတ္၍ အခက္အခဲျဖစ္ေနပါက Mac OS X ၏ Grub ရွိ entry ကို "root (hd0,1) သို႕ေျပာင္းလဲပါ။ထိုသို႕ေျပာင္းလဲျခင္းျဖင့္ သင္၏ကြန္ပ်ဴတာသည္ Partition number 1 ကို boot လုပ္ပါလိမ့္မည္။Grub
မွန္ကန္စြာအလုပ္လုပ္ေဆာင္ႏိုင္သည္အထိ partition number ကို﻿ေျပာင္းလဲႏိုင္သည္။

-------------------

##Package Installation and Updates

###Apt and Package Basics 

**Add Extra Repositories ကိုဖတ္ပါ။**

Ubuntu အသံုးျပဳသူအမ်ားစုသည္ Synaptic Package Manager ကို package မ်ားထည့္သြင္းရန္ 
အသံုးျပဳႀကပါသည္။ ေအာက္ပါ ညႊန္ျပခ်က္မ်ားသည္ package မ်ားကို ကိုpackage မ်ားထည့္သြင္းရန္
အသံုးျပဳႀကပါသည္။ေအာက္ပါညႊန္ျပခ်က္မ်ားသည္ package မ်ားကို command-line Terminal အသံုးျပဳ၍ ထည့္သြင္းရန္ နည္းလမ္းမ်ားျဖစ္ပါသည္။ 

#####Terminal ကိုစတင္ရန္ 
	Menu -> Application -> Accessories -> Terminal

#####packages မ်ားထည့္သြင္းရန္ 

	sudo apt-get install *packagename* 
	ဥပမာ : sudo apt-get install mpd sbackup

#####package မ်ား ဖယ္ရွားရန္

	sudo apt-get remove *packagename*

#####package ႏွင့္တကြ ထို package ႏွင့္ သက္ဆိုင္သည္မ်ားအားလံုး ဖယ္ရွားရန္ 

	sudo apt-get autoremove 
	ဥပမာ : sudo apt-get remove mpd sbackup

#####package မ်ားရွာေဖြရန္ 

	apt-cache search < keywords> 
	ဥပမာ : apt-cache search  Music MP3 apt-cache search "Text Editor"

#####addting/removing repositories ျပဳလုပ္ၿပီး package ၏ database မ်ားကို အဆင့္ၿမႇင့္တင္ရန္ 

	sudo apt-get update

#####package မ်ားကို ugrade လုပ္ရန္ :

	sudo apt-get upgrade

#####Ubuntu စနစ္တစ္ခုလံုးကို upgrade  လုပ္ရန္ (ဥပမာ : Maverick မွ Natty)

	sudo apt-get dist-upgrade

#####deb package မ်ားထည့္သြင္းျခင္း

Debian (.deb) package မ်ားသည္ (Windows ေပၚတြင္installer .exe msi package မ်ား
အလုပ္လုပ္သကဲ့သို႕) Ubuntu ေပၚတြင္ အသံုးျပဳေသာ package မ်ားျဖစ္သည္။ Ubuntu စနစ္ေပၚတြင္ မည္သည့္ .deb package ကိုမဆို ထည့္သြင္းႏိုင္သည္။ Ubuntu စနစ္တြင္ မူလပါရွိေသာ installer ႏွင့္ .deb package မ်ားကို ဆက္သြယ္ႏိုင္ရန္ ျပဳလုပ္ထားသျဖင့္ .deb ဖိုင္မ်ားကို file manager (Nautilus) တြင္ click ျခင္းျဖင့္ လြယ္ကူစြာထည့္သြင္းႏိုင္သည္။ ေအာက္ေဖာ္ၿပပါ ညႊန္ျပခ်က္မ်ားမွာ command-line terminal (Terminal) ကိုအသံုးျပဳႇ၍ package မ်ား ထည့္သြင္းခ်င္သူမ်ားအတြက္ ျဖစ္ပါသည္။

#####အင္တာနက္မွ ဆြဲယူထားေသာ Debian (Ubuntu) package (.deb) ၁ခု ထည့္သြင္းရန္

	sudo dpkg -i packagename.deb

#####Debian (Ubuntu) package (.deb) ကိုဖယ္ရွားရန္ :

	sudo dpkg -r packagename . ဥပမာ : sudo dpkg-reconfigure mpd

------------------

##Handling (Tar/GZip) and (Tar/Bzip2) archives

(Tar/GZip) ရဲ႕ extension က .tar.gz ျဖစ္ပါသည္။ (Tar/Bzip2) ရဲ႕ extension က .tar.bz2 ျဖစ္ပါသည္။ Terminal မွ အသံုးျပဳနည္းမ်ားကို ေအာက္ပါအတိုင္းေဖာ္ျပလိုက္ပါသည္။

	tar xvf  packagename . tar . gz
	-x (ျဖည္ရန္) -v ( ) -f ( )

#####.gz ကိုျဖည္ျခင္း

	gunzip filename .gz

#####.bz2 ကိုျဖည္ျခင္း

#####.gz အျဖစ္ ႏွစ္သက္ရာဖိုင္ကို compress လုပ္ျခင္း

	tar cvfs packagename  .tar.gz folder

#####.bz2 အျဖစ္ ႏွစ္သက္ရာဖိုင္ကို compress လုပ္ျခင္း

	tar cvfj packagename.tar.bz2 folder

-------------------------

##Installing a package from source 

Coming Soon !      
your can contribute

###Aptitude

Aptitude is a terminal-based package manager that can be used instead of apt-get. Aptitude marks package that are automatically installed and removes them when no packages depend on them. This makes it easy to remove application completely. To use Aptitude, replace apt-get with aptitude in the command line.Example

	sudo aptitude install packagename
	sudo aptitude remove packagename 
	sudo aptitude update
	sudo aptitude upgrade

For an ncurses-based graphical user interface, type

	sudo aptitude

For more information, see the aptitude documentation 
(http://people.debian.org/~dburrows/aptitude-doc/en/) .

###Synaptic Package Manager

While apt-get and aptitude are fast ways of installing programs/packages, you can also use the Synaptic Package Manager (Menu - System - Administration - Synaptic Manager ), a GUI method for installing programs/packages.Most (but not all) programs/packages available with apt-get install will also be available from the Synaptic Package Manager.This is the preferred method for most desktop users.In this guide, when you see

	sudo apt-get install package

you can simply search for package in Synaptic and install it that way.

	Menu-System - Administration - Synaptic Package Manager

Search for the name of the program/package. You can also search for a word in its
description.

Mark for Installation -Apply

The selected programs(s) will be automatically installed, along with its dependencies.

###Ubuntu Software Center (Add/Remove Programs)

Package မ်ားအားလံုးသည္ Terminal (apt-get, aptitude, and Synaptic Package Manager)
မွာအဆင္သင့္ မရရွိႏိုင္ေသာ္လည္းပဲ Ubuntu Software Center မွရရွိႏိုင္ပါသည္.မည္သို႕ျဖစ္ေစ ၊ Ubuntu စတင္အသံုးျပဳသူမ်ား အေနျဖင့္ အလြယ္ကူဆံုး ျမင္ကြင္းမွ packages မ်ားအား ေအာက္ပါအတိုင္း ထည့္သြင္းႏိုင္သည္။

	Menu -Application - Ubuntu Software Center

သင္ထည့္သြင္းလိုေသာ Program အခ်ိဳ႕အား ရွာေဖြႏိုင္သည္။ဥပမာ -mp3ဟုရိုက္လွ်င္ mp3
software စာရင္းမ်ား ျမင္ရမည္။

	Installation ျပဳလုပ္လိုေသာ program အားေရြးခ်ယ္ပါ -Apply ႏွိပ္ပါ။ေရြးခ်ယ္ထားေသာ program(s) မ်ားသည္ အလိုအေလ်ာက္ install ျပဳလုပ္သြားမည္။

###Manual Updates

General Notes ကိုဖတ္ပါ။
Add Extra Repositories ကိုဖတ္ပါ။

#####Terminal မွ တဆင့္ ကိုယ္ကိုတိုင္ျပဳလုပ္ရန္အတြက္ (Command Line Interface ):

	sudo apt-get update
	sudo apt-get upgrade

	**သို႕မဟုတ္**

#####Synptic Package Manager ကို အသံုးခ်နည္း

	Menu -System -Administration - Synaptic Package Manager -Reload then Mark all upgrades

အကယ္၍ package က updating လုပ္ဖို႕ အဆင္သင့္ျဖစ္ေနမယ္ဆိုရင္ ခ်က္ျခင္း install လုပ္သင့္ပါတယ္။

###Automated Updates

#####Synaptic Package Manager ကို အသံုးခ်ျခင္း

	Menu - System - Administration - Synaptic Manager - Settings - Preferences - General - Reloading Outdated Package Information - Automatic

------------------------------

##Desktop Add-ons

GNOME Desktop အတြက္ အဆင္သင့္အသံုးျပဳႏိုင္တဲ့ Add-on icons ေတြ themes နဲ႕ Wallpapers မ်ား 3-D effects မ်ားႏွင့္အတူ အျခားေသာ ကိုယ္ကိုယ္တိုင္ ေရြးခ်ယ္ႏိုင္တာေတြ ရွိပါတယ္။

###Gnome Eye-Candy Resources 

[Gnome Look](http://www.gnome-look.org) တြင္ wallpapers ေတြ splash screens ေတြ icons ေတြနဲ႕အတူ  Windows Mangers အတြက္ (Metacity နဲ႕ Compiz ပါ၀င္သည့္) themes မ်ားႏွင့္အျခားေသာ အသံုးျပဳ ေဆာ့၀ဲေတြ (appalication) မ်ားပါရွိပါသည္။

###Ubuntu Wallpaper
[Ubuntu wallpaper](https://www.flickr.com/groups/ubuntuwallpaper/)
[Trusty Tahr Wallpaper](https://www.flickr.com/groups/2535978@N21)
[Ubuntu Myanmar wallpaper](http://flickr.com/groups/ubuntu-mm-art)
ဆိုဒ္မွ အခမဲ့သြားေရာက္ Download ျပဳလုပ္ႏိုင္ပါတယ္။

###Change Plymouth Splash Screen 

Bootup မွာျမင္ရတဲ့ဟာက ကနဦး Splash Screen ျဖစ္ၿပီး အျခားေသာ Plymouth Themes ေတြကို Package Manger မွာသြားေရာက္ ရွာေဖြႏိုင္ပါတယ္။ အသစ္တစ္ခုကို Install ျပဳလုပ္ခ်င္ရင္ေတာ့

	sudo update-alternatives --config default.plymouth
	sudo update-initramfs -u

မိမိႀကိဳက္ႏွစ္သက္ရာ Theme ကို ေရြးခ်ယ္၍ တင္ႏိုင္ပါသည္။ Plymouth ကေတာ့ Bootup ျပဳလုပ္ေနတဲ့အခ်ိန္မွာ မႀကာခဏ Blank Screen မ်ားေပၚေပါက္ျခင္းနဲ႕ nVidia Drivers ေတြ ခ်က္ျခင္း အလုပ္မလုပ္ေဆာင္ႏိုင္ေသးပါဘူး။

###Change USplash Boot Screen

	sudo apt-get install splashy splashy-themes

###Metacity

Metacity ဆိုတာက Gnome မွာပါတဲ့ မူလ Desktop Compositing Manager ပါ။ သူက ေပါ့ပါးျခင္း၊
ခ်က္ျခင္းေျပာင္းလြဲျခင္း (streamlined) ေတြနဲ႕အတူ မ်ားမ်ားစားစားလဲ ျပဳျပင္ေျပာင္းလြဲစရာမလိုတဲ့ Options ေတြပါ၀င္သလို Gnome Look မွာေတာ့ Multiple Themes ေတြ ခ်က္ျခင္း ေဆာင္ရြက္ႏိုင္ျပန္တယ္။

###Compiz Fusion 

Compiz Fusion က window manager နဲ႕ သီးျခားကြဲျပားပါတယ္။ သူက Desktop effects ေတြကို 
အဆင့္ျမင့္ ေျပာင္းလြဲႏိုင္တာျဖစ္ၿပီး Cube တံုးသဖြယ္မ်ိဳး Desktop ကို ေျပာင္းလဲဖန္တီးႏိုင္တာေတြလဲ
ပါဝင္ပါတယ္။Ubuntu Users ေတာ္ေတာ္မ်ားမ်ားက Compiz ကိုေရြးခ်ယ္ အသံုးျပဳႀကပါတယ္။ဒါကို Ubuntu မွာ အခ်ိန္ခဏေလးနဲ႕ အလြယ္တကူ Install ျပဳခ်င္ရင္ေတာ့

	sudo apt-get install compiz compizconfig-settings-manager compiz-fusion-plugins-maincompiz-fusion-plugins-extra emerald librsvg2-common

Compiz ကို Window Manager အျဖစ္ထားခ်င္ရင္ေတာ့ Compiz Configuration မွာ ေအာက္ကအတိုင္း သြားေရာက္ေရြးခ်ယ္ေပးယံုပါပဲ

	Menu - System -Preferences - CompizConfig Settings Manager

မွတ္ခ်က္ ။ ေျပာင္းလြဲထားတာေတြကို အဆင္ေျပဖို႕က Process ၿပီးသြားရင္ Logout လုပ္ၿပီးေတာ့ Login ျပန္လုပ္မွသာ ေျပာင္းလြဲျခင္း effect ကို ျမင္ရမွာျဖစ္ပါတယ္။

###Virtualization

Coming Soon!!!

###Moonlight

See Moonlight plugin for Firefox

###Java

Java install လုပ္ရန္

	sudo apt-get install default-jre

###DosBox

[DosBox](http://www.dosbox.com/) သည္ DOS-emulator (ဆက္စပ္ကိရိယာ) program တစ္ခုျဖစ္သည္။ ၄င္းသည္ `CPU:286/386 realmode/protected mode, Directory FileSystem/XMS/EMS, Tandy/Hercules/CGA/EGA/VGA/VESA grahpics` ႏွင့္ `SoundBlaster/Gravis Ultra Sound card` (ယခင္ဂိမ္းအေဟာင္းမ်ား၏ အသံျဖင့္လိုက္ေလ်ာညီေထြျဖစ္ေစရန္) အသံုးျပဳသည္။ သင္သည္ယခုေခတ္ ကြန္ပ်ဴတာမ်ားေပၚတြင္ ေဆာ့မရေတာ့ေသာ ယခင္ဂႏၶၶၶ၀င္ ဂိမ္းမ်ားအားျပန္လည္အသက္သြင္းႏိုင္ပါလိမ့္မည္။

	sudo apt-get install dosbox

###Scumm VM

[Scumm VM](http://scummvm.org/) သည္ ရုပ္ပံုမ်ားအားညႊန္ၿပျခင္း၊ Click လုပ္ျခင္းစသည့္
ဂိမ္းေဟာင္းမ်ားအား လက္ခံ၍ run ေပးပါသည္။(သင့္တြင္ ၄င္းတို႕၏ ေဒတာဖိုင္မ်ားရွိရပါမည္။) Scumm VM သည္ executables shipped မ်ားတြင္ ေနရာယူ၍ ဂိမ္းမ်ားကို Linux OSတြင္ ကစားခြင့္ေပးမွာျဖစ္ပါတယ္။

	sudo apt-get install scummvm

###Edutainment Applications 

p-26(မရိုက္ထား)

###Google Earth

[Google Earth](http://earth.google.com/) မွ သင့္အား ကၽြႏ္ုပ္တို႕ကမၻာၿဂိဳလ္ႀကီးကို အေပၚစီးက
ျမင္ေတြ႕ခြင့္ေပးမွာျဖစ္ပါတယ္။ဒီ software ဟာ အခမဲ့ package ျဖစ္ပါတယ္။ (ဒီ package ကိုအသံုးျပဳဖို႕အတြက္ License ကို accept လုပ္ရမွာျဖစ္ပါတယ္။)

	sudo apt-get install googleearth-package
	make-googleearth-package --force

ရရွိလာတဲ့ .deb file ကို click ၂ခ်က္ႏွိပ္ပါ။ (သို႕မဟုတ္) Linux အတြက္ ေနာက္ဆံုးထြက္ရွိထားတဲ့ package ကို install လုပ္ရန္အတြက္ [Google Earth downloads](http://earth.google.com/intl/en/download-earth.html) ကိုသြားၿပီး Download ဆြဲပါ။ ၿပီးရင္ ေအာက္က
command နဲ႕ install လုပ္ပါ။  

	wget http://dl.google.com/GoogleEarthLinux.bin/
	chmod  +x GoogleEarthLinux.bin ./GoogleEarthLinux.bin

#####အသံုးျပဳရန္

	Menu - Application -Internet -Google Earth 3D planet viewer

သင့္အေနနဲ႕ Google Earth -View မွာရွိတဲ့ Atmosphere setting ကို turn off လုပ္ထားသင့္ပါတယ္။
ဘာေႀကာင့္လဲဆိုေတာ့ တိမ္ေတြဖံုးေနတာေႀကာင့္ ေျမျပင္ကို ျပမွာမဟုတ္လို႕ပါဘဲ။

#####Troubleshooting

Troubleshooting (ျပင္ဆင္ျခင္း) အကယ္၍ Google Earth ကိုဖြင့္လိုက္တယ္။ Loading ျပဳလုပ္တယ္။ loading ျပဳလုပ္တဲ့ screen တတ္လာၿပီး error ျပမယ္။ဒါမွမဟုတ္ ဘာမွမေပၚေတာ့ဘူးဆိုရင္ေတာ့ သင္ဟာ ျဖစ္ေလ့ျဖစ္ထရွိတဲ့ error တတ္ျခင္းကိုေတြ႕ႀကံဳေနရပါၿပီ။အဲဒီလိုျဖစ္ေနခ်ိန္မွာ Google Earth ကို Terminal ကေန `~/google-earth/googleearth` လို႕ရိုက္ၿပီး run လိုက္ရင္ `./googleearth-bin: relocation error:/usr/lib/i686/cmov/libssl.so.0.9.8: symbol BIO-test-flags, version OPENSSL-0.9.8 not defined in file libcrypto.so.0.9.8 with link time reference` ဆိုတဲ့ error ကိုျပပါလိမ့္မယ္။

ဒီၿပႆနာကိုေျဖရွင္းဖို႕အတြက္သင္ Google Earth ကိုသြင္းထားတဲ့ Folder ကိုဖြင့္လိုက္ပါ။ပံုမွန္အားျဖင့္ေတာ့ Google Earth ဟာ သင့္ home folder ထဲမွာပဲ ရွိေနတတ္ပါတယ္။ ၿပီးရင္ `libcrypto.so.0.9.8` ကိုရွာၿပီး `libcrypto.so.0.9.8.bak` လို႕ေျပာင္းလိုက္ပါ။ Google Earth ဟာ ပံုမွန္အတိုင္း သံုးလို႕ရသြားပါလိ္မ့္မယ္။

	cd ~/google-earth
	sudo mv 
	libcrypto.so.0.9.8 libcrypto.so.0.9.8.bak
	sudo In -s /usr/lib/libcrypto.so.0.9.8~/google-earth/libcrypto.so.0.9.8

>**သတိျပဳရန္** သင့္အေနနဲ႕ `~/google-earth` လို႕ရိုက္မယ့္အစား `/home/user/google-earth` လို႕လဲရိုက္ႏိုင္ပါတယ္)

အျခား ျပႆနာေတြအတြက္ကိုေတာ့ [Ubuntu help pages on Google Earth](https://help.ubuntu.com/community/GoogleEarth) မွာႀကည့္႐ႈႏိုင္ပါတယ္။

#####Google Earth အား Uninstall ျပဳလုပ္ရန္

Uninstall ျပဳလုပ္ဖို႕အတြက္ `/home/user/google-earth Folder` (သင္ Google-earth ကို install ထားတဲ့ folder) မွာရွိတဲ့ uninstall shell script ကို run ပါ။

###FBReader (e-book reader)

[FBReader](http://www.fbreader.org/) သည္ GTK platform ကို အေျခခံထားၿပီး အျခား platform မ်ားတြင္ပါ အသံုးျပဳႏိုင္သည့္ အခမဲ့ e-book reader တစ္ခုျဖစ္သည္။ install ျပဳလုပ္ရန္:

	sudo apt-get install fbreader

###Calibre (e-book reader)

[Calibre](http://calibre-ebook.com) သည္ e-book reader ျဖစ္ၿပီး library manager အျဖစ္လည္း
အသံုးျပဳႏိုင္သည္။ Install ျပဳလုပ္ပံုကို [ဤေနရာတြင္](http://calibre-ebook.com/download-linux)
ႀကည့္ပါ။

----------------------

##Games 

ဂိမ္းမ်ား (K)Ubuntu Linux အတြက္ သဘာ၀က်တဲ့ ဂိမ္းေတြရွိပါတယ္။   

- Ubuntu Community Wiki -- [Games](http://help.ubuntu.com/community/Games).
- [Best Linux Games for 2008](http://whdb.com/2008/top-25-linux-games-for-2008/).
- [Best 25 Linux Games of 2007](http://rangit.com/software/top-8-linux-games-of-2007/).

(K)Ubuntu မွာ ရာေပါင္းမ်ားစြာေသာ အခမဲ့, open-source ဂိမ္းေတြရွိပါတယ္။

- [KDE Games collection](http://www.kde.org/application/games/) နဲ႕ 
- [Gnome Games](http://live.gnome.org/GnomeGames/) collection အပါအ၀င္ အေတာ္မ်ားမ်ားကို သင့္ရဲ႕ Package Manager ထဲက Games Section မွတဆင့္ ရယူႏိုင္ပါတယ္။

ဥပမာတစ္ခ်ိဳ႕ေပးရမယ္ဆိုရင္ 

#####PouetChess
[PouetChess](http://pouetchess.sourceforge.net/) ဟာၿပီးျပည့္စံုတဲ့ 3-D ခ်က္ထိုးတဲ့ Game တစ္ခုပါ။ Install ျပဳလုပ္ရန္      

	sudo apt-get install pouetchess

#####PokerTH
[PokerTH](http://www.pokerth.net/) ဟာအလြန္ကစားရေကာင္းတဲ့ Texas Hold 'Em Poker ပိုကာ Game ပါ။ [PPA repository](https://launchpad.net/~pkg-games/+archive/ppa) အသံုးျပဳၿပီး install လုပ္ႏိုင္ပါတယ္။

#####Kajongg
[Kajongg](http://packages.ubuntu.com/maverick/kajongg) ဟာလူေတြနဲ႕ပဲျဖစ္ျဖစ္၊
စက္ရုပ္ေတြနဲ႕ပဲျဖစ္ျဖစ္ တြဲဖက္/ယွဥ္ၿပိဳင္ကစားရမယ့္ MahJongg (မာေက်ာက္)ကစားနည္းစစ္စစ္ပါပဲ။
Install ျပဳလုပ္ရန္ -

	sudo apt-get install kajongg

#####Planet Penguin Racer
[Planet Penguin Racer](http://en.wikipedia.org/wiki/Tux-Racer) ဟာပင္ဂြင္းငွက္ကေလးဟာ
သံုးဖက္ျမင္ (3-D) အေနအထားနဲ႕ ႏွင္းေလွ်ာစီးသြားမယ္။ ငါးေတြကို ဖမ္းရမွာျဖစ္ပါတယ္။ 

#####Extreme Tux Racer
[Extreme Tux Racer](http://extremetuxracer.com/) ကေတာ့ ေနာက္ေပၚ ဗားရွင္းျဖစ္ေပမယ့္ 32-bit မွာပဲအလုပ္လုပ္ပါတယ္။

#####KsirK
[KsirK](http://games.kde.org/game.php?game=ksirk) ဟာကြန္ပ်ဴတာနဲ႕ပဲျဖစ္ျဖစ္
သူငယ္ခ်င္းနဲ႕ခ်ိတ္ဆက္ၿပီးပဲျဖစ္ျဖစ္ သဲထိတ္ရင္ဖိုေဆာ့ကစားရမဲ့ ဂိမ္းပါ။ Install ျပဳလုပ္ရန္ -

	sudo apt-get install kdegames

#####Racer
[Racer](http://www.racer.nl/) ဟာတကယ့္ကို စိန္ေခၚယွဥ္ၿပိဳင္ႏိုင္တဲ့ 3-D ၿပိဳင္ကားဂိမ္းပါ။ Binary
install ကို [ဒီမွာ](http://www.racer.nl/dl_beta_linux.htm) ေတြ႕ႏိုင္ပါတယ္။ ေျပးလမ္းအသစ္နဲ႕
[extra add-ons](http://www.racer.nl/dl_content.htm) ေတြလည္းရွိပါတယ္။

#####TORCS
[TORCS](http://torcs.sourceforge.net/) ဟာ 3-D ၿပိဳင္ကားဂိမ္းျဖစ္ပါတယ္။ Install လုပ္ရန္ -

	sudo apt-get install torcs

#####Supertuxkart
[Supertuxkart](http://supertuxkart.sourceforge.net/) ဟာၿပိဳင္ကား အေသးစားေလးမ်ားကို ေမာင္းႏွင္ရတဲ့ ဂိမ္းျဖစ္ပါတယ္။ Install ျပဳလုပ္ရန္ - 

	sudo apt-get install supertuxkart

#####Pingus
[Pingus](http://pingus.seul.org/) ရဲ႕ညီအစ္ကိုျဖစ္တဲ့ Lemming (လီမင္) အစား
ပင္ဂြင္းငွက္ကေလးေတြကို အသံုးျပဳထားတာပါ။ Install ျပဳလုပ္ရန္ - 

	sudo apt-get install pingus

#####Frozen Bubble
[Frozen Bubble](http://www.frozen-bubble.org/)--ပူေပါင္းေဖာက္ ကစားနည္းတစ္ခုပါ။ Install
ျပဳလုပ္ရန္ - 

	sudo apt-get install frozen-bubble

#####Frets on Fire
[Frets on Fire](http://fretsonfire.sourceforge.net/) ဟာ Guitar Hero  နဲ႕ ဆင္တူပါတယ္သင့္အေနနဲ႕ Community Site ေတြကေနတဆင့္ [Guitar Hero](http://www.geetarfreaks.webs.com/Viva%20La%20Music.html) ထဲက သီခ်င္းေတြကို
သြင္းယူႏိုင္ပါတယ္။ [community sites](http://fretsonfire.wikidot.com/custom-songs) မွာလဲ
အေသးစိတ္ဖတ္ႏိုင္ပါတယ္။ Install ျပဳလုပ္ရန္ - 

	sudo apt-get install fretsonfire

#####Scorched3d
[Scorched3d](http://www.scorched3d.co.uk/) ဟာႏွစ္ဘက္ျမင္ကို သံုးဖက္ျမင္ (3-
D) အျဖစ္ ကစားႏိုင္မယ့္ အေျမာက္ပစ္ဂိမ္းပါ။ Install လုပ္ရန္ - 

	sudo apt-get install scorched3d

#####Pyscrabble
[Pyscrabble](http://pyscrabble.sourceforge.net/) ႏွင့္ pyscrabble-server -- Online Scrabble(
စကားလံုးမိတ္ဆက္) ဂိမ္းနဲ႕ server ျဖစ္ပါတယ္။ Install ျပဳလုပ္ရန္ -

	sudo apt-get install pyscrabble pyscrabble-server

Lexulou နဲ႕ Internet Scrabble Club တို႕မွာလည္း Scrabble နဲ႕ပံုစံတူ browser-based online
ဂိမ္းေတြရွိပါတယ္။Internet Scrabble Club ကေတာ့ Java ကို install လုပ္ထားဖို႕လိုအပ္ပါတယ္။Java install လုပ္ရန္

	sudo apt-get install default-jre

#####Wing Commander Linux
[Wing Commander Linux](http://priv.solsector.net/) ရဲ႕ အခမဲ့ဗားရွင္းကို Binary ဖိုင္အျဖစ္
ဒီမွာ [Download](http://sourceforge.net/projects/privateer/)ယူႏိုင္ပါၿပီ။

[Vdrift](http://vdrift.net/) သည္ အခမဲ့ open source ျဖစ္ၿပီး Need For Speed ကဲ့သို႕ေသာ realistic, physics, multiple drift tracks, and multiplayer မ်ားပါ၀င္ေသာ 3-D ၿပိဳင္ကားဂိမ္းတစ္ခုျဖစ္သည္။ Joysticks မ်ားျဖင့္ေသာ္လည္းေကာင္း Mice ႏွင့္ keyboard ျဖင့္ေသာ္လည္းေကာင္း အသံုးျပဳႏိုင္သည္။ Linux အတြက္ Binary package အား ထို website မွ download လုပ္၍ ရယူႏိုင္ပါသည္။

###Action Games

အံ့အားသင့္ဖြယ္ရာ အက္ရွင္ဂိမ္းေတြကို (Top 25 မွ ဂိမ္းမ်ားအပါအ၀င္) Ubuntu မွာ ရရွိႏိုင္ပါတယ္။
အေတာ္မ်ားမ်ားကို `Menu - Application - Ubuntu Software Center - Games` ကေနၿပီး install လုပ္ႏိုင္ပါတယ္။ Example အခ်ိဳ႕ကေတာ့-

#####Alien Arena
[Alien Arena](http://icculus.org/alienarena/rpa/about.html) --multi-player first person
shooter အက္ရွင္ဂိမ္းျဖစ္ၿပီးအခမဲ့ server မ်ားနဲ႕ ေဆာ့ကစားႏိုင္ပါတယ္။ 

- (Package : alien- arena)
- (Server : alien-arena-server)


	sudo apt-get install alien-arena
	sudo apt-get install alien-arena-server

#####OpenArena
[OpenArena](http://www.openarena.ws/) -- Open-Source multi-player first person shooter အက္ရွင္ဂိမ္းျဖစ္ၿပီး အခမဲ့ server မ်ားနဲ႕ ေဆာ့ကစားႏိုင္ပါတယ္။

	sudo apt-get install openaren
	sudo apt-get install openarena-server

#####Tremulous
[Tremulous](http://www.tremulous.net) -- Halo နဲ႕ဆင္တူၿပီး multiplayer first person shooter action ဂိမ္းျဖစ္ပါတယ္။ ေနာက္ဆံုးထြက္ ဗားရွင္းအတြက္ Repositories ရွိပါတယ္။

	sudo apt-get install tremulous
	sudo apt-get install tremulous-server

#####Sauerbraten
[Sauerbraten](http://sauerbraten.org/) - Cuber မွျဖစ္ၿပီး Graphic ေကာင္းေကာင္းနဲ႕ multiplayer ေဆာ့ႏိုင္တဲ့ First person shooter game ျဖစ္ပါတယ္။

	sudo apt-get install sauerbraten
	sudo apt-get install sauerbraten-server

#####Nexuiz
[Nexuiz](http://www.alientrap.org/nexuiz/) -- (ၿပိဳင္ပြဲမ်ား) ပါ၀င္တဲ့ open-source multi-player
First person shooter game ျဖစ္ၿပီး free servers မ်ားနဲ႕ေဆာ့ကစားႏိုင္ပါတယ္။

	sudo apt-get install nexuiz
	sudo apt-get install nexuiz-server

ေျမပံု ၃၅ခုပါတဲ့ add-on community pack ကိုေတာ့ [ဒီေနရာမွာ](http://www.alientrap.org/nexuiz/downloads.php) ရရွိႏိုင္ပါတယ္။ အဲတာကို install လုပ္ခ်င္ရင္ေတာ့
map pack ကို `/home/username/.nexuiz/data` (ဒါမွမဟုတ္~ /.nexuiz/data)မွာ ျဖည္ခ်ေပးပါ။ 
> **မွတ္ခ်က္** ဒီထဲက ဂိမ္းေတာ္ေတာ္မ်ားမ်ားဟာ graphics လိုအပ္ခ်က္ေတြရွိပါတယ္။ ဒါေတြကို ေဆာ့မယ္ဆိုရင္ေတာ့သင့္အေနနဲ႕ hardware driver ေတြကို လံုလံုေလာက္ေလာက္ activate လုပ္ထားရပါမယ္။

#####Urban Terror

[Urban Terror](http://www.urbanterror.net) သည္ multiplayer first person shooter အက္ရွင္ဂိမ္း (ဆာဗာထည့္သြင္းၿပီး) ျဖစ္သည္။ ၄င္းသည္ open-source quake 3 engine ကိုအသံုးျပဳထားၿပီး တကယ့္လက္နက္မ်ား၏ အသံုးျပဳႏိုင္မႈမ်ားအား ထည့္သြင္းေပးထားသည္။အခမဲ့ server မ​်ားျဖင့္ multi-player ေဆာ့ႏိုင္ေစရန္ ျပဳလုပ္ေပးထားသည္။ဂ်ာမနီႏိုင္ငံတြင္ လူငယ္မ်ားေဆာ့ကစားခြင့္အား ပိတ္ပင္ထားပါသည္။ Download ျပဳလုပ္ၿပီး [ဤအညႊန္း](http://www.urbanterror.info/docs/texts/110) ကိုအသံုးျပဳကာ install လုပ္ႏိုင္ပါသည္။

#####Domm

Skulltag ရဲ႕[ZDoom](http://zdoom.org/wiki/Compile_ZDoom_on_Linux) နဲ႕ ProBoom (Freedoom) တို႕ဟာ Doom2 ရဲ႕ ဗားရွင္းခြဲေတြျဖစ္ပါတယ္။ Doom3 အတြက္ကိုေတာ့ Ubuntu ေပၚက [Doom3](http://help.ubuntu.com/community/Doom3) မွာ ႀကည့္႐ႈႏိုင္ပါတယ္။

#####Skulltag

[Skulltag](http://skulltag.net/wiki/Installation_for_Ubuntu) သည္ [ZDoom](http://zdoom.org/wiki/Compile_ZDoom_on_Linux) ကို အဆင့္ၿမႇင့္တင္ထားေသာ  ဗားရွင္းျဖစ္ၿပီး
network play ကစားႏိုင္ပါသည္။ (K)Ubuntu တြင္ install လုပ္နည္းအား [website](http://skulltage.net/wiki/Installation_for_Ubuntu)တြင္ ႀကည့္႐ႈႏိုင္ပါသည္။(အကယ္၍သင့္တြင္ မူလ
`Doom2.wad` မရွိပါက ေအာက္တြင္ ေဖာ္ၿပထားေသာ Freedom Iwad ကို အသံုးျပဳႏိုင္ပါသည္။) 

> **မွတ္ခ်က္** Modules အေတာ္မ်ားမ်ားသည္ Universe repositories မွ သီးျခားလိုအပ္ပါသည္။သင့္အေနျဖင့္ Universe repositories ကို enable ျပဳလုပ္ထားရန္လိုအပ္သည္။ `Synaptic Package Manager - Settings - Repositories - Edit Software Sources - Community-maintained Open Source software (universe)` - (အမွန္ျခစ္ေပးပါ။))

Install ျပဳလုပ္ရန္ ႀကိဳတင္ျပင္ဆင္မႈ

	sudo apt-get install timidity timidity-interfaces-extra

ထို႕ေနာက္ skulltage ၏ repositories မ်ား update မ်ားထည့္၍ skulltage ႏွင့္ DoomSeeker(Skulltag online server) အား install ျပဳလုပ္ပါ။

	echo deb http://skulltag.net/download/files/release/deb/jaunty multiverse/ sudo tee /etc/apt/sour
	sudo apt-get update
	sudo apt-get install skulltage doomseeker-skulltag

အကယ္၍ သင့္တြင္ `doom2.wad,tnt.wad` သို႕မဟုတ္ `plutonia.wad` မရွိပါက `freedoom.wad` ကိုသင့္ `~/.skulltag` folder သို႕ copy လုပ္ႏိုင္ပါသည္။

	cd ~/.skulltag
	wget http:/mirror.cinquix.com/pub/savannah/freedoom/freedoom-iwad/freedoom-iwad-0.6.4.zip/
	unzip freedoom-iwad-0.6.4.zip
	cp freedoom+/doom2.wad.
	rm freedoom-iwad-0.6.4.zip

အကယ္၍ သင့္တြင္ (skulltag-server,firewalls ႏွင့္ skulltag ျဖင့္ port forwarding
ျပဳလုပ္ျခင္းတို႕အတြက္)အကူအညီမ်ားလိုအပ္ပါက ဤထပ္တိုး လမ္းညႊန္ခ်က္မ်ားအား ႀကည့္ပါ။

Skulltag ကို မည္သည့္ platform, မည္သည့္ graphics, မည္သည့္ စက္တြင္မဆိုအသံုးျပဳႏိုင္ပါသည္။
၄င္းတြင္ ေထာင္ေပါင္းမ်ားစြာေသာ add-on မ်ား၊ေျမပံုမ်ား၊ gameplay mode မ်ားအား
ေရြးခ်ယ္မကုန္ႏိုင္ေအာင္ အသံုးျပဳကစားႏိုင္ပါသည္။

#####PrBoom

[PrBoom](http://prboom.sourceforge.net/) သည္ မူလ first person shooter action game ျဖစ္သည့္ [Doom2](http://en.wikipedia.org/wiki/Doom_II) သည္ အခမဲ့ open source port ျဖစ္သည္။၄င္းတြင္ ZDoom ၏ advanced option  မ်ားပါ၀င္ျခင္းမရွိပါ။ Freedoom သည္မူလ `Doom2,wad` ကိုေနရာယူမည့္ အခမဲ့ Iwad (ေျမပံုစု)ျဖစ္ပါသည္။

	sudo apt-get install prboom freedoom timidity timidity-interfaces-extra

ဤဂိမ္းအတြက္ ေထာင္ေပါင္းမ်ားစြာေသာ [ ေျမပံု (Wads)](http://www.doomword.com/10years/bestwads/) ရွိပါသည္။သင့္ home directory သည္ သင့္
ေျမပံု (wads) မ်ား သိမ္းဆည္းရန္ အလြယ္ကူဆံုးေနရာျဖစ္ပါသည္။

	mkdir /home/user/wads

သို႕မဟုတ္ အေျပာင္းအလဲအေနျဖင့္ `/user/share/games/doom folder` ကိုအသံုးျပဳ၍ folder
အားမည္သူမဆို အသံုးျပဳႏိုင္ေႀကာင္း ေျပာင္းလဲသတ္မွတ္ေပးႏိုင္ပါသည္။

	chmod -R 777/usr/share/games/doom

သင့္မူလဂိမ္းထဲမွ `doom2.wad,tnt.wad` ႏွင့္ `plutonia.wad` တို႕အား ဤ folder ထဲတြင္ထည့္ပါ။
အကယ္ဤသင့္တြင္မရွိပါက `usr/share/games/freedoom version` မွ `doom2.wad` ကို ဤ 
folder သို႕ copy လုပ္ႏိုင္ပါသည္။သင္ internet မွ Download လုပ္ထားေသာ `.wad` ဖိုင္အသစ္မ်ားကိုလည္း ဤ folder ထဲတြင္ပင္ ထည့္သြင္းပါ။ ၿပီးေနာက္ ဂိမ္းအား မူလ ေျမပံုျဖင့္ျဖစ္ေစ၊သင့္ .wad ေျမပံုသစ္ျဖင့္ျဖစ္္ေစကစားႏိုင္ပါသည္။

	prboom -iwad /home/user/wads/doom2.wad-file /home/user/wads/new_wad.wad

>**မွတ္ခ်က္** `doom2,wad,tnt.wad` သို႕မဟုတ္ `plutonia.wad` တို႕ကိုသာလွ်င္ `iwad` အျဖစ္အသံုးျပဳ၍ ရပါသည္။ သင့္အေနျဖင့္ `wad` အသစ္ထည့္သြင္းအသံုးျပဳလိုပါက အထက္ပါ၃ခုမွ တစ္ခုရွိရပါမည္။ျပႆနာရွိလာပါက `doom2.wad` ကိုသံုးပါ။   


>**မွတ္ခ်က္** ဤဂိမ္းအား `Menu -Applications - Ubuntu Software Center -Games` ရွိ Freedom မွ install လုပ္ယူႏိုင္ပါသည္။ သို႕ေသာ္ `timidity` ႏွင့္ `timidity-interfaces-extra` ကို install ျပဳလုပ္ရန္လိုအပ္ပါသည္။

####MMORPG

#####Spring

The Spring Project  (http://spring, clan-sy.com) သည္ [Star Wars Imperial Winter](http://www.imperialwinter.com/) ႏွင့္ [Complete Annihilation](http://springrts.com/wiki/Complete_Annihilation#Introduction) တို႕ကဲ့သို႕ အခမဲ့ multiplayer ဂိမ္းမ်ားအား
ေရးဆြဲျခင္း၊ကစားျခင္းတို႕အတြက္ scripting engine platform ျဖစ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install spring

#####Regnum Online

[Regnum Online MMPORG](http://www.regnumonline.com.ar/index.php?sec=61=1) အတြက္ အကူအညီလိုအပ္ပါက အေျခခံ [installation](http://ubuntuforums.org/showthread.php?t=615246) ဲျပဳလုပ္နည္းႏွင့္ [help forum](http://www.regnumonline.com.ar/forum/forumdisplay.php?f=15) တြင္ႀကည့္ပါ။

#####PlaneShift 

[PlaneShift](http://www.planeshift.it/) သည္ စိတ္ကူးယဥ္မႈေတြ ျပည့္သိပ္ႏွစ္ၿမဳပ္ေနသည့္ online fantasy ဂိမ္းတစ္ခုျဖစ္သည္။ Client ႏွင့္ patches မ်ားအား [ဒီေနရာတြင္](http://www.planeshift.it/download.html) download လုပ္ႏိုင္ပါသည္။

Download လုပ္ထားေသာ Binary Installation ဖိုင္အား executable ျဖစ္ေအာင္ျပဳလုပ္ပါ။

	cd /directory_where_downloaded
	chmod +x PlaneShift-v0.5.4-x64.bin

root အေနျဖင့္ executable လုပ္ထားေသာဖိုင္အား run ပါ။

	sudo  ./PlaneShift-v0.5.4-x64.bin

Install လုပ္ရမည့္လမ္းညႊန္ခ်က္မ်ားအား လိုက္နာပါ။Whether to manually set permissions
ဟုေမးလာပါက no ဟုေျဖေပးပါ။ Install ျပဳလုပ္ေနစဥ္တြင္ အသံုးျပဳသူေတာ္ေတာ္မ်ားမ်ားသည္ ဂိမ္းအား User အားလံုးအသံုးျပဳႏိုင္ရန္ `/opt` တြင္ install လုပ္ျခင္းထက္ user တစ္ဦးတည္း အသံုးျပဳႏိုင္မည့္ `/home directory` တြင္  install ျပဳလုပ္ျခင္းကို ပိုအေလးေပးႀကသည္။ `/opt` တြင္install လုပ္ျခင္းသည္ အလုပ္ပိုျခင္းေႀကာင့္ျဖစ္သည္။ သင့္ user account အား Games Group တြင္ထည့္သြင္းပါ။

	Menu - System - Administration - Users and Groups - user- Manager Groups -games - Properties - Group Members -user (အမွန္ျခစ္ပါ)-OK

Download the updater patch psupdaterlinux64.zip and unzip it to your download directory. Run the updater as root:

	chmod +x psupdater
	chmod +x psupdater.bin
	sudo ./psupdater---

[PlaneShift Registration](http://www.planeshift.it/register.html)တြင္ စာရင္းသြင္း၍ အခမဲ့
အေကာင့္တစ္ခုလုပ္ပါ။ အကယ္၍ သင္သည္ game ကို menu တြင္ထည့္သြင္းထားပါက `Menu - Applications - Lost Found - Client and Setup` တြင္ရွိပါလိမ့္မည္။

Menu မွ run ခ်င္ပါက Run in terminal ကို အမွန္ျခစ္လုပ္ေပးရပါမည္။ Command-line Terminal မွ run ခ်င္ပါက

	sudo /opt/PlaneShift/pssetup
	sudo /opt/PlaneShift/psclient

>**မွတ္ခ်က္** DSL connection ျဖင့္ 32-bit ဗားရွင္း အသံုးျပဳပါက ေလးပါသည္။

----------------------------

##Internet Applications

သင့္ရဲ႕ Internet connection အား Internet applications မ်ားျဖင့္ အျပည့္အ၀အသံုးျပဳႏိုင္သည္။Web
browsers,Email clients, Instant Messengers, ႏွင့္ အမ်ိဳးအစားအမ်ားပါ၀င္သည္။

###Web Browsers

####Mozilla Firefox 

[Mozilla Firefox](http://www.mozilla.com/en-US/) သည္ေနရာအမ်ားတြင္ ေတြ႕ရသည့္ web browser ျဖစ္သည္။ open source components တြင္ အေျခခံထားေသာ္လည္း သင္၏ အမည္ သို႕မဟုတ္ ကုန္အမွတ္တံဆိပ္ ပါ၀င္ထားၿပီး တခုခုေျပာင္းလဲထားျခင္းျဖင့္ ထပ္မံ ျဖန္႕ျဖဴးႏိုင္မည္မဟုတ္ပါ။ လက္ရွိသံုးေနေသာ version အားတင္ရန္ -

	sudo apt-get install firefox

#####Firefox Plug-ins

######Adblock Plus plug-in (block ads in a web page)

[Adblock Plus](http://adblockplus.org/en/ ျဖင့္ web pages မ်ားတြင္ Blocks ads လုပ္ႏိုင္သည္။
သင့္အေနနဲ႕ subscribe လုပ္ျခင္းျဖင့္ အခမဲ႕ Filter Service ႏွင့္ ေႀကာ္ၿငာမ်ားကို တစ္ခ်က္တည္းႏွင့္ပိတ္ရန္ အတြက္ထပ္ေပါင္းႏိုင္ပါသည္။

	sudo apt-get install xul-ext-adblock-plus

သင့္အေနနဲ႕ ၄င္း extension အား add ရန္ Firefox `Tools - Add -on -Get Add -ons -Search All` Add-ons-AdBlock Plus. (ထိုကဲ့သို႕ လုပ္ေဆာင္လွ်င္ firefox အေနျဖင့္ automatic updates
လုပ္ေဆာင္ေပးလိမ့္မည္။)

[Noscript](http://noscript.net/) သည္ Internet ေပၚတြင္ browsing လုပ္ရာတြင္ Sercuriy တိုင္းတာခ်က္အရ အေရးႀကီးပါ၀င္မႈ တစ္ခုျဖစ္သည္။Scripts မ်ားျဖင့္ Internet မွတဆင့္ Viruses မ်ားႏွင့္ Trojans တို႕သည္ computers သို႕ေရာက္ရွိသည္။၄င္း plugin ျဖင့္ မည္သည့္ scripts အား Allow ႏွင့္ blocks the rest လုပ္မည္ကို ေရြးခ်ယ္ႏိုင္သည္။ ၄င္း extension အား add ရန္ Firefox - `Tools - Add -ons -Get Add-ons -Search All Add -ons-Noscript.` (ထိုကဲ့သို႕လုပ္ေဆာင္လ်င္ firefox အေနျဖင့္ automatic updates လုပ္ေဆာင္ေပးလိမ့္မည္။)

######RefreshBlocker plug-in (prevents redirects)

[RefreshBlocker](https://addons.mozilla.org/en-US/firefox/addon/refreshblocker/) သည္ မည္သည့္ website(and pages)အား redirect(based on  META tags within the webpage ျပဳလုပ္ရန္အတြက္ user မ်ားအား ဆံုးျဖတ္ေပးသည္။သို႕ေပေသာ္လည္း Firefox (as of version 3.5) တြင္ အားလံုး directs လုပ္ျခင္းကို blocks လုပ္သည္မွာ default ျဖစ္သည္။ စိတ္ႀကိဳက္မဟုတ္သည့္အတြက္ေႀကာင့္ firefox redirect control အား  turnoff လုပ္ၿပီး ၄င္းအစား RefreshBlocker သံုးသည္။ သင့္အေနနဲ႕ ၄င္း extension အား add ရန္ Firefox - `Tool -Add-ons-Get Add-ons -Search All Add-ons-RefreshBlocker.`(ထိုကဲ့သို႕လုပ္ေဆာင္လ်င္ firefox အေနျဖင့္ automatic updates လုပ္ေဆာင္ေပးလိမ့္မည္။

######Turn off the Firefox  automatic redirect bloker  

Firefox - Enter about : config in the browser location bar-right-click on
accessibility:blockautorefresh - Toggle to change the value from true to false


######User Agent Switcher plug-in for Firefox

[User Agent Switcher](http://chrispederick.com/work/user-agent-switcher/) သည္ အျခားေသာ browser  ကဲ့သို႕ အေယာင္ေဆာင္ျခင္းကို ျပဳလုပ္သည္ခြင့္ျပဳျခင္း (အခ်ိန္လြန္) broser-specific ပါရွိေသာအေႀကာင္းအရာမ်ားကို displayed ျပဳလုပ္ရန္။

သင့္အေနနဲက ၄င္း extension အား add ရန္ Firefox - `Tool -Add-ons-GetAdd-ons- Search All Auto-ons-User Agent Switcher.`(ထိုကဲ့သို႕လုပ္ေဆာင္လ်င္ firefox  အေနျဖင့္ automatic updates လုပ္ေဆာင္ေပးလိမ့္မည္။

######Video DownloadHelper plug-in for Firefox

[Video DownloadHelper](http://addons.mozilla.org/en-US/firefox/addon3006) သည္ youtube ကဲ့သို႕ေသာ site မ်ားမွ videos (Flash Videos အပါအ၀င္) ကို download ရယူရန္ျဖစ္သည္။

သင့္အေနနဲ႕ ၄င္းextension အား add ရန္ Fierfox - `Tools -Add -ons- Get Add -ons-Search All Add-ons-Video DownloadHelper.` (ထိုကဲ့သို႕ လုပ္ေဆာင္လ်င္ firefox အေနျဖင့္ automatic 
updates လုပ္ေဆာင္ေပးလိမ့္မည္။) 

######Unplug Download Management

[UnPlug](https://addons.mozilla.org/en.US/firefox/addon/2254) add-on သည္ webpag ေပၚတြင္ embedded လုပ္ထားေသာ video ႏွင့္ Audio မ်ားကို Save လုပ္ယူႏိုင္သည္။

သင့္အေနျဖင့္ ၄င္း extension အား add ရန္ Firefox - `Tool- Add-ons-Get Add-ons-Browse All Add-ons.` (ထိုကဲ့သို႕လုပ္ေဆာင္လ်င္ firefox အေနျဖင့္ automatic updates
လုပ္ေဆာင္ေပးလိမ့္မည္။)

######Lucifox (eBook reader  extension)

[Lucifox](https://addons.mozilla.org/en-US/firefox/addon/lucifox/) (Lucidor for Firefox) သည္ e-book မ်ားကို ဖတ္ရန္ႏွင့္ Firefox window မွေန catalogs မ်ားကို browsed လုပ္ေပးႏိုင္ရန္ျဖစ္သည္။ Install ျပဳလုပ္ရန္ယ website သို႕သြားၿပီး ေနာက္ Download Now ေနရာတြင္ရယူႏိုင္သည္။

######Java Runtime Environment (JRE) for Firefox plug-in

ယခု package သည္ Java Runtime Enviroment install ႏွင့္တူညီသည္။ (OpenOffice Installed ေသာအခါ or ubuntu-restricted -extras installed ေသာအခါ JRE  ပါ၀င္သည္။)

	sudo apt-get install sun-java6-jre sun-java6-plugin

>**မွတ္ခ်က္** သင့္အေနျဖင့္ product ကိုအသံုးျပဳရန္ product license အား မလြဲမေသြ လက္ခံရမည္။

######Adobe Acrobat Reader for Firefox Plug-in

၄င္း pluging သည္ Adobe Acrobat(pdf) files မ်ားကို firefox browser တြင္ ႀကည့္ရန္ျဖစ္သည္။
Read Add Extra Kubuntu Repositories and enable the Natty partner repository :

	deb http://archive.canonical.com/ubuntu natty partner/	

ၿပီးပါက Adobe Reader ထည့္သြင္းရန္ :

	sudo apt-get install acroread

သို႕မဟုတ္ပါက ၄င္း plugin အား the Medibuntu repository list တြင္လည္း ရရွိႏိုင္သည္။
Medibuntu repository အား သင့္ရဲ႕ repository list တြင္ထည့္ရန္ :

	deb http://packages.medibuntu.org// natty free non-free

ၿပီးပါက Adober Reader ထည့္သြင္းရန္ :

	sudo apt-get install acroread mozilla-acroread acroread-plugins acroread-fonts

######Adobe Flash Player for Firefox Plug-in

Firefox အတြက္ offical Adobe Flash Plugin 10 အား တင္ရန္ :

	sudo apt-get install adobe-flashplugin

######Gnash Plug-in (Open source Flash Player replacement)

[Gnash](http://www.gnashdev.org/) သည္ 32-bit version ကဲ့သို႕ 64-version အတြက္လည္း
ရယူႏိုင္သည္။ ၄င္းသည္ Adobe Flashplayer အတြက္ source အား ေျပာင္းလဲႏိုင္သည္။

	sudo apt-get install gnash

installing ၿပီးေနာက္, သင့္ web browser ရဲ႕ Preference - Application ထဲရွိ `SWF and SPL files` မွားကို `Gnash` ျဖင့္သံုးမည္ဟု ေႀကၿငာရမည္။

######VLC plug-in for Firefox

၄င္း package သည္ ယခုလက္ရွိ အသံုးမ်ားေသာ VIC player အား Firefox browser ရွိ play media 
တြင္ အသံုးျပဳသည္။

	sudo apt-get install mozilla-plugin-vlc

######Gecko MediaPlayer Plug-in for Firefox

[Gecko MediaPlayer](http://kdekorte.googlepages.com/gecko-mediaplayer) သည္ Gecko-based broswers (Firefox,SeaMonkey,IceApe,Opera) မ်ားတြင္ Mplayer မွ multimedia သို႕ သံုးျပဳသည္။

	sudo apt-get install gecko-mediaplayer

ေနာက္တစ္ခုအေနျဖင့္ Firefox အတြက္ mplayer အားသံုးျပဳႏိုင္သည္။

	sudo apt-get install mozilla-mplayer

######Kaffeine Plug-in for Firefox

၄င္း package ျဖစ္သည့္ the Kaffeine media player (often used in KDE-based desktops) သည္ Firefox browser တြင္ multimedia အျဖစ္လုပ္ေဆာင္သည ္။

	sudo apt-get install kaffeine-mozilla

######Helix player plug-in for Firefox

၄င္း package ျဖစ္သည့္ [Helix player](https://helixcommunity.org/) (the open source player that plays Real Player content in Linux) သည္ Firefox browser တြင္ RealMedia အျဖစ္လုပ္ေဆာင္သည္။

	sudo apt-get install mozilla-helix-player

######Moonlight plugin for Firefox

[Moonlight](http://www.go-mono.com/moonlight) သည္ Silverlight (the Microsoft multimedia presentation platform) အား open source အျဖစ္လုပ္ေဆာင္ရန္ ႀကိဳးစားေနေသာ the Novell Mono ၏ project ျဖစ္သည္။၄င္းသည္ FFMpeg အမ်ိဳးအစားျဖစ္သည္။ Firefox 3 web browser တြင္ ေကာင္းေကာင္းသံုးႏိုင္ရန္ျပဳလုပ္ထားၿပီး, plugin ကဲ့သို႕(အျခားေသာ mozilla browsers ေကာင္းေကာင္းသံုးႏိုင္ရန္ျပဳလုပ္ထားၿပီး, plugin ကဲ့သို႕(အျခားေသာ mozilla browsers
မ်ားတြင္လည္းလုပ္ႏိုင္သည္။)mozilla-based browsers ျဖစ္ေသာ Version 2.3 တြင္လည္း plugin အျဖစ္ လုပ္ေဆာင္ႏိုင္သည္။

	sudo apt-get install moonlight-plugin-mozilla

stable version 2.4 အား [ဒီေနရာတြင္](http://www.go=mono.com/moonlight/stable.aspx)
ရႏိုင္သည္။ The Moonlight 3.99 plugin (compatible with most Silverlight 3/4 content) အား
[ဒီေနရာတြင္](http://www.go--mono.com/moonlight/prerelease.aspx) ရႏိုင္သည္။

######Netflix under Moonlight

Netflix streaming အတြက္လိုအပ္ခ်က္ႏွစ္ခုမွာ the capabilities of Silverlight 2.0 ႏွင့္ Digital Rights Management modules ျဖစ္သည္။သို႕ေပေသာ္လည္း လက္ရွိအမ်ိဳးအစားျဖစ္ေသာ Moonlight 2.0 တြင္လည္း Silverlight content (including Netflix content) သံုးႏိုင္သည္ ,linux အတြက္ Digital Rights Management modules အား Netfilix မွ အဆင္သင့္မျဖစ္ေသးပါ။ ေက်းဇူးျပဳၿပီး [Netflix](http://www.netflix.com/ContactUs) သို႕တိုက္ရိုက္ဆက္သြယ္ၿပီး သတင္းရယူႏိုင္ပါသည္။သို႕မဟုတ္ [ဤေနရာတြင္](http://www.petitiononline.com/Linflix)  မွတ္ပံုတင္ၿပီး ေတာင္းဆိုႏိုင္ပါသည္။ (Chrome browser အတြက္Google မွျပဳလုပ္ေနေသာ)An HTML5 Netflix plugin မႀကာမီ သံုးစြဲႏိုင္ေတာ့မည္။အျခားေသာ နည္းလမ္းတစ္ခုအေနနဲ႕ Netflix Android app အား virtual Android environment တြင္လည္း သံုးစြဲႏိုင္သည္။

######FireFTP for Firefox

FireFTP (http://fireftp.mozdev.org/) သည္ Firefox extension တြင္ FTP transfers အတြက္ျဖစ္သည္။

#####Firefox Widgets

Turn off browser bar drop-down list in Firefox

Firefox တြင္ drop-down list ရွိ browser bar အားပိတ္ထားရန္။

၎သည္ Firefox တြင္ တစ္ခါတစ္ရံမွသာ ျဖစ္ေပၚတတ္ေသာ ျပႆနာျဖစ္သည္။ drop-down list ရွိ location browser bar အား ပိတ္ထားရန္ (http://kb.mozillazine.org/Browser.urlbar.maxRichResults) (ထိုသို႕ျပဳလုပ္ျခင္းျဖင့္ သင့္ browsing history အားျပသေတာ့မည္မဟုတ္ပါ။)

Firefox -  about:config (in the location browser bar) - browser.urlbar.maxRichResults-right-click-Modify-set value to 0

######IceCat

IceCat (http://en.wikipedia.org/wiki/GNU_IceCat) သည္ Mozilla ၏ ကုန္အမွတ္တံဆိပ္ မူပိုင္ခြင့္၊ တားျမစ္ခ်က္မ်ားမရွိေသာ Firefox အေျချပဳ Browser တစ္ခုျဖစ္သည္။Debian project မွေထာက္ပံ႕ေပးသည္။ ယခင္က IceWeasel နာမည္ႏွင့္ျဖစ္ၿပီး၊ယခု IceApe Browser နာမည္သို႕ ေျပာင္းလိုက္သည္။ေနာက္ဆံုး version ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install iceape-browser

######SeaMonkey

[SeaMonkey](http://www.seamonkey-project.org/) သည္ web browser, IM (IRC) client, Email client,RSS/News reader ႏွင့္ အျခား web development tools မ်ားပါ၀င္ေသာ အင္တာနက္ application တစ္ခုျဖစ္ပါသည္။Mozilla ၏ ထုတ္ကုန္မ်ားကို အေျခခံထားၿပီး၊ Mozilla ၏ မူပိုင္ခြင့္၊ ျဖန္႕ေ၀သံုးစြဲခြင့္မ်ားႏွင့္ ဆက္စပ္ေနသည္။ Thunderbird ႏွင့္ Firefox ကဲ့သို႕ Seamonkey အတြက္ Plugins အေျမာက္အမ်ားရွိသည္။ Seamonkey ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install seamonkey

######IceApe

[IceApe](http://en.wikipedia.org/wiki/Naming_conflict_between_Debian_and_Mozilla) သည္ web browser, IM (IRC) client, Email client, RSS/News reader ႏွင့္ web development tools မ်ားပါ၀င္ေသာ open-source အင္တာနက္ application တစ္ခုျဖစ္သည္။ Seamonkey ကို အေျခခံထားၿပီး၊ မူပိုင္ခြင့္ ကန္႕သတ္ထားျခင္းမ်ားမရွိေပ။ Debian project မွေထာက္ပံ႕ေပးထားေသာ application ျဖစ္သည္။ ေနာက္ဆံုး version ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install iceape

####Opera

[Opera](http://www.opera.com/) သည္ မူပိုင္ခြင့္ကန္႕သတ္ခ်က္ရွိေသာ proprietary browser, internet suite တစ္ခုျဖစ္သည္။ Mobile devices အခ်ိဳ႕ႏွင့္ game consoles မ်ားတြင္လဲ အသံုးျပဳႏိုင္သည္။ Email, address book, IRC chat, integrated BitTorrent ႏွင့္ webfeeds မ်ားပါ၀င္သည္။ Plugins အနည္းငယ္လဲရွိသည္။ Install လုပ္ေဆာင္ရန္ Opera ၏ website မွ Download (http://www.opera.com/browser/download/) လုပ္ၿပီး၊ လမ္းညႊန္ခ်က္မ်ား ဆက္လုပ္ပါ။ သို႕မဟုတ္ ေအာက္ပါ command မ်ားကို အသံုးျပဳၿပီး Opera repository မွတဆင့္ Install လုပ္ႏိုင္သည္။

	echo "deb http://deb.opera.com/opera/ stable non-free" | sudo tee /etc/apt/sources.list.d/opera.list
	wget -O - http://deb.opera.com/archive.key | sudo apt-key add -
	sudo apt-get install opera

####Chromium

[Chromium](http://dev.chromium.org/) သည္ Google Chrome browser ကို အေျခခံထားေသာ open- source browser တစ္ခုျဖစ္သည္။ Chromium ကို Install လုပ္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္း ရိုက္ထည့္ပါ။

    sudo apt-get install chromium-browser

Chromium ကို အသံုးျပဳရန္ ေအာက္ပါအတိုင္းသြားပါ။

Menu - Applications - Internet - Chromium Web Browser

####Google Chrome

[Google Chrome](http://www.google.com/chrome) သည္ Google မွထုတ္ေသာ browser တစ္ခုျဖစ္သည္။ Chromium browser ကိုအေျခခံထားၿပီး၊ Google ၏ နာမည္၊ လိုဂိုအမွတ္တံဆိပ္၊ GoogleUpdate ဟုေခၚသည့္ အလိုအေလ်ာက္ Update စနစ္၊RZL ႏွင့္ အျခား Google add-ons မ်ားပါ၀င္သည္။ Google Chrome ကို ဤေနရာမွ (http://www.google.com/chrome/eula.html) ေဒါင္းလုတ္လုပ္ၿပီး၊ install လုပ္ပါ။

###Download Managers

Browsers မ်ားထက္ ေဒါင္းလုတ္လုပ္ငန္းစဥ္ လြယ္ကူၿပီး၊ပိုမိုျမန္ဆန္ေစရန္၊ အမွားနည္းေစရန္ ျပဳလုပ္ထားေသာ ေဆာ့လ္၀ဲမ်ားျဖစ္သည္။အခ်ိဳ႕ Download Managers မ်ားတြင္ အင္တာနက္ ကြန္နက္ရွင္မေကာင္းပါက ခဏရပ္တန္႕ထားၿပီး၊ ေနာင္ ကြန္နက္ရွင္ျပန္ေကာင္းမွ ဆက္လက္ေဒါင္းလုတ္ႏိုင္ေသာ Resuming Downloads Option လဲပါ၀င္သည္။

####MultiGet

[MultiGet](http://multiget.sourceforge.net/) သည္ ေဒါင္းလုတ္လုပ္ငန္းစဥ္မ်ား လြယ္ကူေစရန္ အသံုးျပဳႏိုင္သည့္ Download Manager တစ္ခုျဖစ္သည္။ GTK ကို အေျခခံထားၿပီး GUI (Graphical User Interface) ႏွင့္ျဖစ္သည္။ HTTP/FTP စနစ္တို႕ကို ေထာက္ပံ႕ၿပီး၊ Resuming Downloads ကိုလဲ လုပ္ေဆာင္ႏိုင္သည္။ SOCKS 4,4a,5 proxy, ftp proxy, http proxy တို႕ႏွင့္လဲ အသံုးျပဳႏိုင္သည္။ MultiGet ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါ command ကိုရိုက္ထည့္ပါ။

    sudo apt-get install multiget

####Usenet Clients

Usenet Clients ဆိုသည္မွာ ယခင္တုန္းက အသံုးျပဳႀကေသာ အင္တာနက္ေပၚရွိ Discussions Group တစ္ခုျဖစ္သည္။ယခုေခတ္ အသံုးမ်ားႀကေသာ ဖိုရမ္မ်ား၏ ေရွ႕ေဆာင္လမ္းျပတစ္ခုျဖစ္သည္။ ဖိုရမ္မ်ားကဲ့သို႕ပင္ ပို႕စ္မ်ားတင္ျခင္း၊ အျခားသူမ်ားတင္ထားေသာ ပို႕စ္မ်ားကိုဖတ္႐ႈျခင္းမ်ား ျပဳလုပ္ႏိုင္သည္။ေဆြးေႏြးခ်က္မ်ား၊ ပို႕စ္မ်ားကိုသက္ဆိုင္ရာ က႑အသီးသီးအလိုက္ စုစည္းထားၿပီး newsgroupဟုေခၚသည္။ ေဆြးေႏြးခ်က္မ်ားကိုလည္း Threads မ်ားခြဲထားသည္။ Usenet Discussion Group မွ ေဆြးေႏြးခ်က္မ်ားကို ဖတ္႐ႈရန္ Usenet Clients ဟုေခၚေသာ ေဆာ့လ္၀ဲမ်ားသံုးရန္ လိုအပ္သည္။

####Pan
[Pan](http://pan.rebelbase.com/) Pan သည္ Usenet မွ ေဆြးေႏြးခ်က္မ်ားကို ဖတ္႐ႈရန္ အသံုးျပဳႏိုင္သည့္ Gnome-based ေဆာ့လ္ဝဲလ္တစ္ခုျဖစ္သည္။ nzb (http://en.wikipedia.org/wiki/Nzb) binary downloader တစ္ခုလဲ ျဖစ္သည္။ Pan ကို Install လုပ္ရန္ Terminal တြင္ ေအာက္ပါ Command ကို႐ိုက္ထည့္ပါ။

    sudo apt-get install pan 

####Kwooty

[Kwooty](http://kwooty.sourceforge.net/) သည္ Usenet မွ ေဆြးေႏြးခ်က္မ်ား ဖတ္႐ႈရန္အတြက္ KDE4 တြင္အသုံးျပဳႏိုင္သည့္ ေဆာ့လ္ဝဲတစ္ခုျဖစ္သည္။ nzb (http://en.wikipedia.org/wiki/Nzb) binary downloader တစ္ခုလဲျဖစ္သည္။ Kwooty ကို Install လုပ္ေဆာင္ရန္အတြက္ လိုအပ္ေသာ Files မ်ား၊ PPA repositories မ်ား၊လမ္းၫႊန္ခ်က္မ်ားကို Kwooty website တြင္ ၾကည့္႐ႈႏိုင္ပါသည္။

###Instant Messengers

mIRC, Gtalk ကဲ့သို႔ ခ်က္တင္လုပ္ျခင္း၊ စကားေျပာျခင္း၊video calling မ်ားလုပ္ေဆာင္ႏိုင္ေသာ
ေဆာ့လ္ဝဲတစ္မ်ိဳးျဖစ္သည္။

####Empathy

[Empathy](http://live.gnome.org/Empathy) ဆိုသည္မွာ Open Source IM ေဆာ့လ္ဝဲလ္တစ္ခုျဖစ္ပါသည္။ ဤေဆာ့လ္ဝဲသည္ Ubuntu (Gnome) အသုံးျပဳေသာ desktop မ်ားတြင္ ပုံမွန္ပါ၀င္ေသာ ေဆာ့လ္ဝဲတစ္ခုလည္းျဖစ္သည္။

    sudo apt-get install empathy

####Pidgin

[Pidgin](http://www.pidgin.im/) ေဆာ့လ္ဝဲလ္သည္ Open Source IM ေဆာ့လ္ဝဲလ္တစ္ခု ျဖစ္သည္။ ဤေဆာ့လ္ဝဲလ္သည္ Ubuntu (Gnome) အသုံးျပဳေသာ desktop မ်ားတြင္ ပုံမွန္ပါ၀င္ေသာ ေဆာ့လ္ဝဲလ္တစ္ခုလည္းျဖစ္သည္။ ယခုလက္ရွိ Empathy ကိုသာ ပုံမွန္ အစားထိုးသုံးလ်က္ရွိေသာ္လည္း ျမန္မာျပည္၏ MPT လိုင္းႏွင့္ အျခားေသာ Proxy ထည့္သြင္းရေသာ လိုင္းမ်ားအတြက္သင့္ေတာ္သည္။

    sudo apt-get install pidgin

#####အသုံးျပဳပုံ

- Add Account လုပ္ပါ။
- Basic Tab ထဲမွာ ေအာက္ပါအတိုင္းျဖည့္ပါ။

```
**Login Options**
protocol    : XMPP
username    : gmailaccount (@gmail ျဖည့္ရန္မလိုပါ)
Domain      : gmail.com
```

- Advanced Tab တြင္ ```Force old (port 5223) SSL``` ကိုအမွန္ျခစ္ေပးပါ။
- ```Connect port``` တြင္ ```443``` ျဖည့္ပါ။
- ```Connect server``` တြင္ ```talk.google.com``` ျဖည့္ပါ။
- အားလုံးၿပီးလၽွင္ Add ကိုႏွိပ္ပါ။

ၿပီးလၽွင္ ခ်ိတ္ဆက္ အသုံးျပဳႏိုင္ပါသည္။

####Kopete

[Kopete](http://kopete.kde.org/) ဆိုသည္မွာ Kubuntu Os (KDE) အတြက္ default ပါ၀င္ေသာ ခ်က္တင္ေဆာ့လ္ဝဲျဖစ္သည္။

    sudo apt-get install kopete

#####Kopete Styles

Kopete အတြက္ [ပုံစံ](http://www.kde-look.org/index.php?xcontentmode=24x26) ကို ထည့္သြင္းၿပီး Kopete တြင္ မိမိႏွစ္သက္ရာ ပုံစံမ်ားကို ေအာက္ေဖာ္ျပပါေနရာတြင္ ေျပာင္းလဲႏိုင္ပါသည္။

    Kopete > Settings > Configure > Chat Windows > Style > Get New...

#####GoogleTalk on Kopete

Kopete ကိုအသုံးျပဳၿပီး [GoogleTalk](http://www.google.com/talk/about.html) Instant Messaging အသုံးျပဳႏိုင္ေသာ္လည္း VOIP ကို အသုံးမျပဳႏိုင္သျဖင့္ အသံဆက္သြယ္ျခင္း ရမည္မဟုတ္ပါ။ Jabber Protocol ကိုသုံးထားသည္။ ဤေနရာတြင္ေလ့လာပါ [GoogleTalk instructions](http://www.google.com/support/talk/bin/answer.py?answer=57557).

####Konversation (IRC client)

Konversation (http://konversation.kde.org/) သည္ kubuntu တြင္ default ပါ၀င္ေသာ IRC ခ်က္ ေဆာ့လ္ဝဲလ္ျဖစ္သည္။ mIRC အလားတူေဆာ့လ္ဝဲလ္ တစ္ခုျဖစ္သည္။

    sudo apt-get install konversation

####aMSN

aMSN သည္ MSN ရဲ႕ client ေဆာ့ဝဲကဲ့သို႔   အသုံးျပဳႏိုင္ေသာ ေဆာ့ဝဲတစ္ခုျဖစ္သည္။ Pidgin တြင္လည္း အလားတူသုံးႏိုင္သည္။

    sudo apt-get install amsn

သင့္အင္တာနက္လိုင္းအေနျဖင့္ အဆင္ေျပႏိုင္မေျပႏိုင္ မသိေသာ္လည္း ဖိုင္မ်ား လြယ္ကူစြာ
ဆြဲယူကူးေျပာင္းႏိုင္မႈကို Ubuntu Geek (http://www.ubuntugeek.com/how-to-enable-drag-and-drop-capabilities-to-amsn.html) တြင္ ဖတ္႐ႈႏ္ိုင္သည္။

####Emesence

[Emesence](http://www.emesene.org/) သည္ ႐ိုးရွင္းေသာပုံစံျဖင့္ ျပဳလုပ္ထားေသာ MSN messager တစ္ခုျဖစ္သည္။ အလားတူပင္ [#Pidgin l Pidgin] တြင္လည္း အသုံးျပဳႏိုင္ပါသည္။

    sudo apt-get install emesene

####Videoconferencing and VOIP

ယခုအခါ Videoconferencing ႏွင့္ Voice Over Internet (VOIP) တို႔တို Application တစ္ခုတည္းအျဖစ္  ေပါင္းစပ္လာၿပီျဖစ္သည္။ တခ်ိဳ႕ဆိုလၽွင္ internet ခ်ိတ္စပ္မထားေသာ ဖုန္းမ်ားကိုပင္ အသက္သာဆုံး ႏႈန္းထားျဖင့္ ေခၚဆိုႏိုင္ေနၿပီျဖစ္သည္။ 

####Ekiga

ယခင္ Gnomemeeting ဟုသိခဲ့ၾကသည့္ [Ekiga](http://www.gnomemeeting.org/) သည္ SIP အား အျပည့္အ၀လိုက္နာသည့္ function အျပည့္အစုံပါ VOIP ႏွင့္ Video စနစ္ပါ အသုံးျပဳႏိုင္ေသာ ပ႐ိုဂရမ္ျဖစ္သည္။

    sudo apt-get install ekiga


####Skype

[Skype](http://www.skype.com/) သည္ Ekiga ကဲ့သို႔ VOIP ႏွင့္ Video စနစ္သုံး ဆက္သြယ္ေရး
ပ႐ိုဂရမ္ျဖစ္ေသာ္လည္း Open-Source မဟုတ္ပါ။ Skype ဆက္သြယ္မႈမ်ားအား [guide](http://help.ubuntu.com/community.SkypeRecordingHowto)

Install ျပဳလုပ္ႏိုင္ရန္ package တခ်ိဳ႕ လိုအပ္ပါသည္။

    sudo apt-get install libqt4-dbus libqt4-network libqt4-xml

ေနာက္ဆုံးထြက္ ဗားရွင္းအား ရယူရန္ႏွင့္ 32 -bit ဗားရွင္းအား download ႏွင့္ install ျပဳလုပ္ရန္

```
wget -O skype-ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
sudo dpkg -i skype-ubuntu-current_i386.deb
sudo rm skype-ubuntu-current_i386.deb
```

ယခင္က အခ်ိဳ႕ သုံးစြဲသူမ်ားသည္ ၎တို႔၏ မိုက္ခ႐ိုဖုန္းမ်ားအား 2.1.0.47 ေနာက္ပိုင္း ဗားရွင္းမ်ားတြင္ 	သုံးစြဲ၍ မရေသာေၾကာင့္ ေအာက္ေဖာ္ျပပါ command မ်ား သုံးခဲ့ၾကသည္။

```
wget -O skype-ubuntu-current_i386.deb http://download.skype.com/linux/skype-debian_2,1.0.47-1
sudo dpkg -i skype-ubuntu-current_i386.deb
sudo rm skype-ubuntu-current_i386.deb
```

######ေနာက္တစ္နည္း

```
wget -O skype-ubuntu-current_amd64.deb http://download.skype.com/linux/skype-ubuntu-intrepid
sudo dpkg -i skype-ubuntu-current_amd64.deb
sudo rm skype-ubuntu-current_amd64.deb
```

#####How to install Skype on a 64-bit system

Skype အား 64-bit system မ်ားတြင္ install ျပဳလုပ္နည္း 64-bit system အတြက္ Skype ၏ လက္ရွိ version သည္ 32 bit module အား 64 အတြက္ အသုံးျပဳထားျခင္းျဖစ္သည္။ 64 bit system တြင္ install ျပဳလုပ္ရန္အတြက္ အျခား package မ်ားအား ဦးစြာ install ျပဳလုပ္ရန္ လိုအပ္သည္။

```
sudo apt-get install ia32-libs lib32asound2 libqt4-core libqt4-gui bqt4 - core libqt4 - gui
```

ၿပီးေနာက္ လက္ရွိ Skype version ၏ .deb package အား Skype website မွ download ျပဳလုပ္၍ 
	install ျပဳလုပ္ပါ။

    wget -O skype_ubuntu-current_amd64.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-64
    sudo dpkg -i skype-ubuntu-current_amd64.deb
    sudo rm  skype-ubuntu-current_amd64.deb

အကယ္၍ 64-bit version သည္ သင့္အတြက္ အလုပ္မလုပ္ပါက 32-bit version အား အသံုးျပဳႏိုင္သည္။

    wget -O skype_ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
    sudo dpkg -i --force -architecture  skype_ubuntu-current_i386.deb
    sudo rm  skype_ubuntu-current_i386.deb


#####Installing Skype respository

Skype ၏ respository ထည့္သြင္းျခင္းအားျဖင့္လည္း Skype အား install လုပ္ႏုိင္ပါသည္။
ဤသို႔ျပဳလုပ္ျခင္းျဖင့္ auto update ျပဳလုပ္ေပးသည့္ အက်ဳိးေက်းဇူးရွိပါသည္။

-Resopsitory security key အား install လုပ္ရန္ (key server အတြက္ သင့္ firewall ၏ port 11371
	အား ဖြင့္ထားရန္လိုအပ္သည္။

    sudo apt - key adv -- keyserver pgp.mit.edu --recv -keys 0xd66b746e


#####Skype repository,update ထည့္ျခင္းႏွင့္ Skype အား install ျပဳလုပ္ျခင္း။

    echo deb http://download.skype.com/linux/repos,debian/ stable non-free l   sudo tee - a
    sudo apt-get update
    sudo apt-get install skype

------------------------

##Proprietary Extras
မူပိုင္ခြင့္အရ မွတ္ပံုတင္ထားေသာ ထပ္ေဆာင္း package မ်ား မူပိုင္ခြင့္အရ မွတ္ပံုတင္ထားသည့္ software မ်ားသည္ အင္တာနက္ အသံုးျပဳရာတြင္ မ်ားစြာအေထာက္အကူျပဳပါလိမ့္မည္။ သို႔ေသာ္ လြတ္လပ္စြာ ရယူသံုးစြဲခြင့္မရွိပါ ။ Multimedia Codecs မ်ား၊ Java Runtime Environment ႏွင့္ Firefox အတြက္ plug-in မ်ားသည္ ထိုကဲ့သို႔ေသာ software မ်ားျဖစ္သည္။

--------------------------

##Restricted Extras
###ကန္႔သတ္ထားေသာ ထပ္ေဆာင္း package မ်ား

Ubuntu တြင္ ကန္႔သတ္ထားေသာ ထပ္ေဆာင္း package မ်ားကို ထည့္သြင္းလိုလွ်င္ command-line Terminal တြင္  command တစ္ခုတည္း ရိုက္ထည့္ရံုျဖင့္ လုပ္ေဆာင္ႏုိ္င္ပါသည္။ ထုိ package မ်ားတြင္ `Adobe Flash Player`, `Jave Runtime Environment (JRE) (sun-java-jre)` ႏွင့္ `Firefox plug-in (icedtea)` မ်ား, Microsoft မွ ထုတ္ေ၀ေသာ `Font` တခ်ဳိ႔ `(msttcorefonts)`, `multimedia codecs (w32codecs or w64codecs)`, `mp3 compatible encoding (lame)`, `FFMpeg`, `extra Gstreamer codecs`, DVD decoding အတြက္ package မ်ား (`libdvdread4`, သို႔ေသာ္ အျခား decoder ျဖစ္သည့္ `libdvdcss2` ကို
ရယူလိုပါက ဤေနရာတြင္ၾကည့္ပါ။), `unrar archiver`, `odbc` ႏွင့္ `cabextract`မ်ားပါ၀င္သည္။ ထို႔အျပင္ အျခားေသာ အက်ဳိးအျမတ္ရယူသည့္ codecs မ်ားႏွင့္ `avutils (libavcodec - unstripped - 52` ႏွင့္ `libavutil-unstripped - 49`) မ်ားကိုလည္း ထည့္သြင္းေပးမည္ျဖစ္သည္။

    sudo apt-get install ubuntu-restricted-extras  

>**မွတ္ခ်က္** ထည့္သြင္းျခင္း လုပ္ငန္းစဥ္အတြက္ command-line Terminal တြင္ လုပ္ေဆာင္ခ်က္မ်ားၿပီးဆံုးမွသာ ျပည့္စံု၍ အလုပ္လုပ္ေဆာင္ႏုိင္မည္ျဖစ္သည္။  ယခုေဖာ္ျပထားေသာ package အားလံုးကို Package Manager အသံုးျပဳ၍ ထည့္သြင္းပါက ျပည့္စံုမည္မဟုတ္ပါ။

--------------------------------

##Photos and Graphics

သင္၏ဓာတ္ပံုမ်ားကို ျပင္ဆင္ထိန္းသိမ္းျခင္း၊ ရင္သပ္ရႈေမာဖြယ္ 3D ပံုမ်ားႏွင့္ ဂရပ္ဖစ္မ်ားကို ဖန္တီးျခင္္း
သို႔မဟုတ္ Format ဖိုင္အမ်ဳိးအစား ေျပာင္းလဲျခင္းမ်ား ျပဳလုပ္ရန္။

###GIMP (Image Manipulator)

[Gimp](http://www.gimp.org/) သည္ အစြမ္းထက္ေသာ စြမ္းရည္ျပည့္၀သည့္ free open-source ျဖစ္ပါသည္။
ဂရစ္ဖစ္မ်ားႏွင့္ ဓာတ္ပံုမ်ားျပင္ဆင္သည့္ Adobe Photoshop ႏွင့္  ဆင္တူေသာ ေဆာ့ဖ္၀ဲျဖစ္ပါသည္။

    sudo apt-get install gimp

####GIMP အတြက္ သီးသန္႔ brushe မ်ား palette မ်ားႏွင့္ gradiend မ်ားရိွပါသည္။

    sudo apt-get install gimp-data-extras
 

###Dia (Diagram editor)
 
[Dia](http://live.gnome.org/Dia) သည္ Gnome အတြက္ ျပဳလုပ္ထားသည့္ GTK အေျခခံ diagram
ဖန္တီးသည့္ open source ပရိုဂရမ္ျဖစ္ပါသည္။ Visio ႏွင့္  ဆင္တူပါသည္။

sudo apt-get install dia

###Kivio (Diagram editor)

[Kivio](http://www.koffice.org/kivio/) သည္ flow-chat မ်ားႏွင့္ diagram မ်ားကို ဖန္တီးသည့္  open source ပရိုဂရမ္ျဖစ္ၿပီး KDE အတြက္ ျပဳလုပ္ထားသည့္ KOffice Suite တြင္ ပါ၀င္ပါသည္။ Dia ဖေယာင္းမိတၱဴမ်ား ျပဳလုပ္၍ ရပါသည္။

    sudo apt-get install kivio

###Inkscape  Vector Illustrator

[Inkscape Vector Illustrator](http://www.inkscape.org/) သည္ Illustrator ၊CorelDraw စသည္တုိ႔ႏွင့္ 
တူညီသည့္ open source  ပံုဆြဲပရိုဂရမ္ျဖစ္ပါသည္။

    sudo apt-get install inkscape

###Digikam (Photo Organiser)

[Digikam](http://www.digikam.org) သည္ ဒစ္ဂ်စ္တယ္ ဓာတ္ပံုမ်ားကို ျပင္ဆင္ စုစည္းသိမ္းဆည္းဖို႔
အလြန္အဆင္ေျပေသာ open source ျဖစ္ပါသည္။ install လုပ္လိုလွ်င္

    sudo apt-get install digikam kipi-plugins digikam-doc

###F -spot (Photo Organiser)

[F -spot](http://htpp://f-spot.org/) သည္ ဒစ္ဂ်စ္တယ္ဓာတ္ပံုမ်ားကို ျပင္ဆင္စုစည္းသိမ္းဆည္းဖို႔
အလြန္အဆင္ေျပေသာ Gnome Desktop အတြက္ ျပဳလုပ္ထားသည့္ open source ျဖစ္သည္။ install
လုပ္လိုပါက:

    sudo apt-get install f-spot


###Google Picasa (Photo Organiser)

[Google Picasa](http://picasa.google.com.mm/linux/) သည္ Digikam ကဲ့သို႔ ပင္
ဓာတ္ပံုျပင္ဆင္သိမ္းဆည္းရန္ျဖစ္ပါသည္။ အြန္လိုင္းအသံုးျပဳထားပါက Google web server သုိ႔ 
တိုက္ရိုက္ပံုမ်ားကို upload လုပ္ႏုိင္ပါသည္။ အေသးစိ္တ္သိလိုပါက Picasa for Linux FAQ
(http://picasa.google.com/linux/faq.html) တြင္ ၾကည့္ပါ ။ Picasa 2.7 Download
(http://picasa.google.com/linux/download.html#picasa27) ေနရာတြင္ ကုိယ္တိုင္ install လုပ္ႏုိင္သည့္
.deb ဖိုင္ရရွိႏိုင္ပါသည္။

###Shotwell (Photo Organiser)

[Shotwell](http://www.yorba.org/shotwell/) အလြယ္တကူ ၾကည့္ရႈ ထိန္းခ်ဳပ္ႏိုင္မည့္ ေဆာ့၀ဲတစ္ခုျဖစ္ပါသည္။  ဤေနရာ (http://www.youba.org/shotwell/install/) တြင္ အေသးစိတ္ ၾကည့္ရႈပါ။

#####Terminal မွ သြင္းရန္

    sudo add-apt-repository ppa:yorba/ppa
    sudo apt-get update
    sudo apt-get install shotwell

###Tesseract (Optical Character Reader)

Tesseract (http://code.google.com/p/tesseract-ocr/) သည္ command-line ျဖင့္ အသံုးျပဳႏိုင္သည့္ optical character reader တစ္ခုျဖစ္ပါသည္။ Install  ျပဳလုပ္ရန္:

    sudo apt-get install tesseract -ocr

[Ocropus](http://code.google.com/p/ocropus/) သည္ Tesseract ကို အသံုးျပဳထားသည့္ document - analysis engine တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္:

    sudo apt-get install ocropus

###Xsane (Scanning utility)

[Xsane](http://www.xsane.org/) သည္ Scan ဖတ္ရန္ အသံုးျပဳႏိုင္သည့္ ေဆာ့၀ဲလ္တစ္မ်ဳိးျဖစ္ပါသည္။ Xsane ကို  Install လုပ္ရန္ Terminal တြင္ ေအာက္ပါ Command ကို ရိုက္ထည့္ေပးပါ။

    sudo apt-get install xsane


###Gnome - Scan (Scanning Utility)

[Gnome - Scan](http://projects.gnome.org/gnome-scan/) သည္ Scan ဖတ္ရန္ အသံုးျပဳႏိုင္သည့္
ေဆာ့၀ဲလ္တစ္မ်ဳိးျဖစ္ပါသည္။ Gnome - Scan ကို Install လုပ္ရန္ Terminal တြင္ ေအာက္ပါ Command
ကို ရိုက္ထည့္ပါ။

    sudo apt-get install gnomescan 


###Gwenview (Image Manipulator)

Gwenview (http://gwenview.sourceforget.net/) သည္ KDE တြင္ ဓာတ္ပံုမ်ားၾကည့္ရန္ အသံုးျပဳႏုိင္ေသာေဆာ့လ္၀ဲ တစ္မ်ဳိးျဖစ္သည္။ ပံုမ်ားကို rotate လုပ္ျခင္း၊ crop လုပ္ျခင္း၊ resize လုပ္ျခင္း စသည့္အေျခခံတည္းျဖတ္မႈမ်ားလည္း ျပဳလုပ္ႏုိင္သည္။ Gwenview ကို Kubuntu တြင္ defaultအေနႏွင့္ ထည့္သြင္းထားသည္။ (K menu - Graphics - Gwenview Image Viewer) Gwenview ကို Installလုပ္လိုပါက Terminal တြင္ ေအာက္ပါ Command ကို ရိုက္ထည့္ပါ။

    sudo apt-get install openclipart

##Screencasts and Desktop Recording

Coming Soon!!!

------------------------

##Video Applications

###Webcam Applications

ဤေဆာ့၀ဲမ်ားသည္ Webcam အသံုးျပဳေသာေဆာ့၀ဲမ်ားျဖစ္ပါသည္။မိမိတို႔ပံုမ်ားကို Effect မ်ား ထည့္သံုး၍ 
အလြယ္တကူအသံုးျပဳႏုိင္ေသာ ေဆာ့၀ဲမ်ားျဖစ္သည္။

####Cheese
[Cheese](http://projects.gnome.org/cheese/) သည္ Gnome-based webcam
 ေဆာ့၀ဲတစ္ခုျဖစ္ၿပီး ေဆာ့၀ဲ ၍ window size ကိုလဲ လိုအပ္သလို ျပဳလုပ္အသံုးျပဳႏုိင္ပါသည္။

Terminal မွ သြင္းရန္

    sudo apt-get install cheese

####Kamoso
 
[Kamoso](https://kde-apps.org/content/show.php/Kamoso?content=111750) သည္
KDE-base webcam ေဆာ့၀ဲတစ္ခုျဖစ္သည္။

    sudo apt-get install kamoso

####Camorama
[Camorama](http://camorama.fixedgear.org/index.php) သည္ Cheese ကဲ့သို႔ေသာ webcam 
ေဆာ့၀ဲတစ္ခုျဖစ္ၿပီး Gtk based ေဆာ့၀ဲတစ္ခုျဖစ္သည္။

    sudo apt-get install camorama

####Xawtv

[Xawtv](http://git.linuxtv.org/xawtv4.git) သည္ Cheese ကဲ့သို႔ေသာ webcam
ေဆာ့၀ဲတစ္ခုျဖစ္ၿပီး Gtk based ေဆာ့၀ဲတစ္ခုျဖစ္သည္။ ScreenCasts ျပဳလုပ္ရန္ အသံုးတည့္ေသာ 
အမ်ဳိးအစားျဖစ္သည္။

Click on X in the window bar-Advanced -No Border(ticked)

    sudo apt-get-install xawtv

ဤေဆာ့၀ဲမ်ားကို Gnome/KDE Ubuntu ႏွင့္ Kubuntu မ်ားတြင္ အသံုးျပဳႏိုင္ပါသည္။

-----------------------------------------

##Office Suites

###Open Office

[Open Office](http://www.openoffice.org) ကို Ubuntu တြင္ ပံုမွန္အေနျဖင့္ ထည့္သြင္းၿပီးျဖစ္သည္။ ပါ၀င္ေသာ ေဆာ့၀ဲမ်ားႏွင့္ ႏႈိင္းယွဥ္ျပရလွ်င္ --Writer (Word ကဲ့သို႔ သံုးႏိုင္သည္),Presentation (PowerPoint ကဲ့သို႔  သံုးႏိုင္သည္),Calc spreadsheet (Excel ကဲ့သို႔ သံုးႏုိင္သည္) , ႏွင့္ Base relational database (Access ကဲ့သို႔ သံုးႏိုင္သည္)

####Word 2007 အား Open Office တြင္အသံုးျပဳျခင္း

ေနာက္ဆံုးထြက္ Open Office  သည္ .docx ဖိုင္ (Word 2007) ဖိုင္မ်ားအား ပံုမွန္အတိုင္း အသံုးျပဳႏုိင္ၿပီ ျဖစ္သည္။

###Libre Office

[Libre Office](https://www.libreoffice.org/) သည္ free and open source (GPL-licensed) office suite တစ္ခုျဖစ္ၿပီး ယခင္က OpenOffice ႏွင့္ အတူတူပင္ျဖစ္သည္။ Install ျပဳလုပ္ရန္:

    sudo add-apt-repository ppa:libreoffice/ppa
    sudo apt-get update
    sudo apt-get install libreoffice libreoffice-gnoma

###KOffice

[KOffice](http://www.koffice.org/) သည္ KDE project ၏ တစိတ္တေဒသျဖစ္ၿပီး OpenOffice suite ၏ လုပ္ေဆာင္ခ်က္မ်ားအား OpenOffice လိုင္စင္ေအာက္မွ မဟုတ္ဘဲ အသံုးျပဳႏိုင္ရန္ျဖစ္သည္။ ဤ program အား မည္သည့္ ubuntu ဗားရွင္းတြင္မဆို အသံုးျပဳႏုိင္သည္။ Install ျပဳလုပ္ရန္

    sudo apt-get install koffice

###Abi Word

[Abi Word](http://www.abisource.com/) သည္ လွ်င္ျမန္ၿပီး စုေပါင္းလုပ္ေဆာင္ႏုိင္ေသာ စာစီစာရိုက္စနစ္ျဖစ္သည္။ ေနာက္ဆံုးထြက္ ဗားရွင္းအား ၾကည့္ရန္ [Abi Word website](http://abisource.com/com/wiki/Install-on-Ubuntu) ကို သြားပါ။ Repositories မွ install လုပ္ရန္

    sudo apt-get install abiword

###Xournal

[Xournal](http://xournal.sourceforge.net/) သည္ အခမဲ့ (GPL-licensed) ျဖစ္ၿပီး မွတ္စု ေရးသားျခင္း။ ပံုၾကမ္းဆြဲျခင္း (သို႔မဟုတ္) stylus အသံုးျပဳ၍ ဂ်ာနယ္မ်ား သိမ္းဆည္းျခင္းမ်ားအတြက္ GTK/Gnome အား အေျခခံထားသည့္ အသံုးခ် software ျဖစ္သည္။ Install ျပဳလုပ္ရန္ universe repositories အား enable ျပဳလုပ္ထားရမည္။

    sudo apt-get install xournal

###PDF Files

[PDF](https://en.wikipedia.org/wiki/Portable-Document-Format) ဖိုင္သည္ Adobe Acrobat (အျခားe-book readers မ်ားတြင္ ဖတ္ရႈႏုိင္ေသာ) Format တစ္ခုျဖစ္သည္။ Ubuntu တြင္ PDF ကဲ့သို႔ ဖိုင္မ်ားအတြက္ အသံုး၀င္သည့္ program အမ်ားအျပားရွိပါသည္။ Synaptic Package Manager တြင္ pdf ကို ရိုက္၍ ရွာေဖြၾကည့္ပါ။

####Print to a PDF File

(K) Ubuntu သည္ မည္သည့္ Document (စာရြက္စာတမ္း) ကိုမဆို PDF Format သို႔ အလိုအေလ်ာက္ ထုတ္ခြင့္ျပဳပါသည္။ မည္သည့္ application မွမဆို File- Print -Print to File - Output:PDF

####View a PDF document

[Evince](http://projects.gnome.org/evince/) သည္ PDF ဖိုင္မ်ား ၾကည့္ရႈရန္အတြက္
အလိုအေလ်ာက္ ထ﻿ည့္သြင္းၿပီးသားျဖစ္သည္။ PDF ဖိုင္မ်ားသည္ Evince ႏွင့္ အလိုအေလ်ာက္ဖြင့္ႏုိင္သည္။ ထို႔ေၾကာင့္ PDF ကို click  လုပ္လိုက္ပါက (Nautilus ကဲ့သို႔ေသာ File manager မွ ဖြင့္ပါက) Evince ႏွင့္ အလိုအေလ်ာက္ပြင့္မည္ျဖစ္သည္။ Evince ကို ဤသို႔လည္း စတင္အသံုးျပဳႏုိင္သည္။


####Menu- Office - Evince

???

####Print PDF documents

The CUPS Print manager has a plugin to seamlessly print PDF documents. Install:

	sudo apt-get install cups-pdf

???

####Scan to a PDF file

[Gscan2pdf](http:// gscan2pdf.sourceforge.net/) is a utility to do exactly that: scan to a PDF file. Multiple options for scanning can be set.Install:

	sudo apt-get install gscan2pdf

####PDF -Shuffler (PDF file management)

[PDF - Shuffler](http://sourceforge.net/projects/pdfshuffler/files/) is a free GTK-based utility to manipulate multiple PDF files,allowing individual pages or entire PDF documents to be re-arranged, rotated, merged, or deleted. This is an essential tool for working with PDF files.Install:

	sudo apt-get install pdf-shuffler

Run:

	Menu - Office - PDF - Shuffler

####Max View (PDF File management)

[Max View](http://sourceforge.net/projects/maxview/) is utility to capture , manipulate and rearrange,and print `.pdf` and `.max` files. Written in Qt, it is similar in some respects to Paperport. [Download](http://sourceforge.net/projects/max view 0.7-2/) and install the `.deb` package (use i386 instead of amd64 if using a 32-bit OS):

	wget - O maxview current.deb http://sourceforge.net/projects/maxview/files/maxviewo.7-2/maxvie
	sudo dpkg- i  maxview current .deb

Start Max View in a GUI by creating a menu item with the Command: maxview
/home/user, where /home/user is the directory in which you wish Max View to start.

####PDF edit (PDF File editor)

[PDF edit](http://pdfedit.petricek.net/en/index.html) is a free (GPL - licensed), Qt - based PDF  file editing and manipulation program that uses a GUI for editing.Install:

	sudo apt-get install pdfedit

####Import PDF files into a word processor

####Import PDF files into Open Office Writer

[PDF files can be imported](htt://extensions.services.openoffice.org/project/pdfimport) into the OpenOffice Writer word processor as a hybrid document ( not a scanned character document ) by installing:

	sudo apt-get install openoffice.org-pdf import

####Import PDF files into K Word

Kword is the Word Processor package in K Office.It allows the importing of PDF files by 
default.

####PDF- X Change (PDF file editor)

[PDF-X Change](http://www.tracker-software.com/product/pdf-xchange-viewer) is a free
Windows-based application to view,modify,or perform simple editing of PDF files.It works under Wine.

-------------------------------

##Personal Information Managers

Coming Soon !!!

you can contribute.

###Groupware

Groupware တြင္  ေ၀မွ်သံုးေသာ ျပကၡဒိန္မ်ား၊ Email server စုစည္းထားမႈမ်ား၊ အစုအသင္းမ်ား၏ လိပ္စာ စာရင္းမ်ား၊ အသင္းအဖြဲ႔မ်ား၏ စီမံကိန္းမ်ား ႏွင့္ အသင္းအဖြဲ႔မ်ားအတြင္း message ပို႔ျခင္းမ်ား ပါ၀င္သည္။ ၎တို႔သည္ LAMP (သို႔) အလားတူ ဆာဗာမ်ား တစ္ခု (သို႔) တစ္ခုထက္ပို၍ လိုအပ္သည္။

####Groupware Servers

Groupware servers မ်ားမွာ Server platform ေပၚတြင္ အသံုးျပဳရန္ ရည္ရြယ္ထားျခင္းျဖစ္သည္။
သင့္အေနျဖင့္ သီးသန္႔ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ဆာဗာတစ္ခုအတြက္ (အျမန္ႏႈန္းေကာင္းေစရန္အတြက္) Ubuntu server version အား တပ္ဆင္ထားသင့္သည္။

###Kolab

[Kolab](http://www.kolab.org/) သည္အျပည့္စံုဆံုးေသာ  Open- source groupware ျဖစ္ၿပီး platform မ်ဳိးစံုအတြက္ ျဖန္႔ခ်ီထားသည္။ ၎တို႔သည္ Ubuntu (Evolution အပါအ၀င္) KDE/Kunbuntu (Kcontact အပါအ၀င္) တို႔ႏွင့္ ေကာင္းစြာ ေပါင္းစပ္အလုပ္လုပ္ႏုိင္သည္။   ၎သည္ အခမဲ့၊ GPL လိုင္စင္ျဖင့္ ပြင့္လင္းရင္းျမစ္ျဖစ္ေသာ္လည္း (အျခားအုပ္စုဖြဲ႔ ေဆာ့၀ဲမ်ားႏွင့္ မတူသည့္အခ်က္မွာ) စီးပြားေရးလုပ္ငန္းသံုးအတြက္ အကူအညီရျခင္းပင္ျဖစ္သည္။  ၎သည္ ႀကီးမားေသာ အဖြဲ႔အစည္းမ်ားအတြက္ အသံုးျပဳႏိုင္သည့္အျပင္ Outlook (MS -Exchange) ႏွင့္ Mozilla တို႔ႏွင့္လည္း တြဲဖက္ႏိုင္သည္။ သို႔ေသာ္ဂ်ာမန္ထုတ္ျဖစ္သည့္အတြက္ အဂၤလိပ္ဘာသာျဖင့္ အသံုးျပဳနည္းတြင္ အကန္႔အသတ္မ်ား ရံဖန္ရံခါ ရွိတတ္သည္။ 

Kolab ၀က္ဘ္ဆိုက္တြင္ ရင္းျမစ္မွ တပ္ဆင္ပံု (ယခုလက္ရွိ ဗ.၂.၂) အတြက္ ညႊန္ၾကားခ်က္မ်ား ေပးထားသည္။ ဗားရွင္း ၂.၂ တြင္ Horde ၀က္ဘ္ပံုစံပါ၀င္သည္။ လက္ရွိ ဘီတာအဆင့္ ဒီဘီရန္းအတြက္ ညႊန္ၾကားခ်က္မ်ားမွာ [HERE](http://wiki.kolab.org/index.php/Debian) - Administrators - Kolab-Installation (သို႔) OpenPkg အတြက္ ညြန္ၾကားခ်က္မ်ားမွာ [HERE](http://files.kolab.org/server/release/kolab-server-2.2.4/ix86-debian5.0/1st.README)

>**မွတ္ခ်က္**  Kolab သည္   ၎ကိုယ္ပိုင္ ဆာဗာအစိတ္အပိုင္းမ်ားကို အသံုးျပဳျခင္းျဖင့္ 
Kolab ကို သီးသန္႔ဆာဗာေပၚတြင္ အသံုးျပဳျခင္းသည္ အေကာင္းဆံုးျဖစ္သည္။ သို႔ေသာ္လည္း မတူညီေသာ port မ်ားကို ေရြးခ်ယ္ေပးျခင္းျဖင့္ အျခားေသာ ဆာဗာမိုဂ်ဴးမ်ားျဖင့္ ပဋိပကၡ ျဖစ္ျခင္းကို ေရွာင္လႊဲကာစက္တစ္လံုးတည္းေပၚတြင္ အျခားေသာ ဆာဗာမ်ားကိုပါ တပ္ဆင္အသံုးျပဳႏုိင္သည္။  

compiler ႏွင့္အျခားေသာ လုိအပ္သည့္ အရာမ်ားကို တပ္ဆင္ရန္

	sudo apt-get install build-essential

####Kolab Ubuntu package

အသံုးျပဳနည္း မပါ၀င္ေသးေသာ Kolab version အသစ္ (v.2.2) Ubuntu/ Kubuntu အတြက္လည္း ရွိပါသည္။ တပ္ဆင္ရန္မွာ

	sudo apt-get install kolabd

####Manual Kolab installation

Kolab တပ္ဆင္ရန္အတြက္ ဖိုလ္ဒါတစ္ခုေဆာက္ပါ။ ၎ကို အားလံုး အသံုးျပဳခြင့္ေပးပါ။

	sudo mkdir/ kolab
	sudo chmod 777 / kolab

**Optional**: kolab ကို   ၎ အတြက္ ကိုယ္ပိုင္ အပိုင္းတြင္ တပ္ဆင္လိုပါက ဦးစြာ အပိုင္းသစ္ အရင္ျပဳလုပ္ပါ။ (ဥပမာ - Gparted ကို သံုး ၍ ) ထို႔ေနာက္  ၎အပိုင္းအတြက္ နာမည္ေပးပါ။

	sudo rdisk - 1

၎သည္ `/dev/sda3` ကဲ့သို႔ ျဖစ္ရမည္။ အဆိုပါ `/deb/sda3` (သင္ျပဳလုပ္ေသာအပိုင္း ) ကို `/etc/fstab` ျပဳလုပ္ျခင္းအားျဖင့္  `/kolab` အျဖစ္တင္ပါ။

	sudo nano / etc /fstab 

ထို႔ေနာက္ ေနာက္တစ္ေၾကာင္း ထပ္ေပါင္းပါ။

	/dev/sda3/kolab  ext3   defaults , rw  0  0

ထို႔ေနာက္ restart ျပဳလုပ္ျခင္းျဖင့္ အမွား ကင္းျခင္း ရွိမရွိ စစ္ေဆးပါ။ kolab အား download ျပဳလုပ္ထားသည့္  ေနရာတြင္  folder တစ္ခုျပဳလုပ္ပါ။ လက္ရွိ  Kolab file မ်ားအား Download ျပဳလုပ္ရန္  Folder တစ္ခု တည္ေဆာက္ပါ။

	cd /tmp
	mkdir   /kolabtmp

နာက္ဆံုးထြက္ရွိသည့္  Kolab file မ်ားအား Download ျပဳလုပ္ပါ။

	cd /tmp/kolabtmp

	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/ix 86-debian4.0
	
	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/sources/

Root အေနျဖင့္ sudo-s ကို အသံုးျပဳကာ Kolab အား install ျပဳလုပ္ပါ :

	sudo-s
	sh install - kolab.sh 21  l  tee kolab - install .log

သင့္ ကြန္ပ်ဴတာအား restart ျပဳလုပ္ပါ။ Kolab service မ်ားအား ရပ္ဆိုင္း၍  Configuration utility ကို ဖြင့္ပါ။

	sudo /kolab/bin/openpky rc all stop
	sudo /kolob/sbin/kolab bootstrap -b

သင့္အေနျဖင့္ မိမိ၏ အခ်က္အလက္မ်ားျဖစ္သည့္ host ၏ အမည္ ၊ (၎ ကို  hostname - f ျဖင့္ သိႏိုင္သည္) domain အေသးစိတ္အခ်က္အလက္ စသည္တို႔အား ဤအဆင့္ မျပဳလုပ္မီတြင္ သိရွိထားသင့္ပါသည္။ Kolab သည္ slabd open LDAP server တို႔ကို အသံုးျပဳမည္ျဖစ္ေသာေၾကာင့္ [Open LDAP](http://www.openldap .org /) ႏွင့္ [LDAP](http://en.wikipedia.org/ wiki /LDAP) ၏ အေျခခံအခ်က္အလက္မ်ားႏွင့္ ရင္းႏွီးကၽြမ္း၀င္မႈ မရွိေသးပါက သင့္အေနျဖင့္ ေလ့လာထားသင့္ပါသည္။

Kolab ၏ service မ်ားအားလံုးအား ျပန္လည္စတင္ပါ။

	sudo / kolab /bin /openpkg rc all start

Manager အား အသံုးျပဳ ၍ bootstrap configuration တြင္ ထည့္သြင္းထားသည့္ password ျဖင့္ web
administrator interface သို႔ Login ျပဳလုပ္ပါ။

	http://yourhost.yourdomain.name/admin/

###Citadel

[Citadel](http://www.citadel.org/) သည္ အသင့္သံုး open source groupware ျဖစ္ၿပီး KDE ႏွင့္ Kolab-1 ႏွစ္မ်ဳိးလံုးျဖင့္ တြဲဖက္အသံုးျပဳႏုိင္သည္။ လြန္ခဲ့သည့္ ႏွစ္ေပါင္း ၂၀ေက်ာ္မွ Bulletin - board ပံုစံ framework အား အသံုးျပဳထားေသာေၾကာင့္  ၎သည္ KDE , Gnome ႏွစ္မ်ဳိးစလံုးျဖင့္ရ ၀က္ဘ္ အေျချပဳ ပံုစံလည္း သံုးစြဲႏို္င္သည္။ WebDAV ႏွင့္လည္း တြဲဖက္ႏို္င္ၿပီး Thunderbird ျဖင့္ လည္း အသံုးျပဳႏုိင္သည္။

####Install the Citadel server:

	sudo apt-get install citadel-server

####Install the Citadel client:

	sudo apt-get install citadel-client

####Install both:

	sudo apt-get install citadel-suite

####eGroupware

[eGroupware](http://www.egroupware.org/) သည္ အေျခခံခိုင္မာ တည္ၿငိမ္ေသာ (GPL လိုင္စင္ျဖင့္) ပြင့္လင္းရင္းျမစ္ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္ၿပီး LAMP (ဦးဘႏၱဳ ဆာဗာျဖင့္ တပါတည္း ပါရွိေသာ ဆာဗာ) ႏွင့္ Postfix mail (ႏွစ္မ်ဳိးစလံုးကို ဦးတည္ထည့္သြင္းထားသင့္ပါသည္ )ေပၚတြင္ အေျခခံထားသည္။ ဗားရွင္းအသစ္ကို မၾကာေသးမီကပင္ ရရွိႏုိင္ၿပီး ဂ်ာမနီမွ ေကာ္ပိုရိတ္စပြန္စာျဖင့္ စီးပြားေရးလုပ္ငန္းသံုး ဗားရွင္းတို႔ပါ၀င္သည္။ Clients မ်ားျဖင့္ တြဲဖက္အသံုးျပဳႏိုင္မႈမွာ မ်ားစြာတိုးတက္လာပါသည္။ eGroupware သည္ အစုအဖြဲ႔ ေဆာ့၀ဲလ္မ်ားအားလံုးတြင္ အလြယ္ကူဆံုးႏွင့္ အျမန္ဆံုးေသာ တပ္ဆင္ခ်ိန္ကို ေပးစြမ္းႏုိင္ပါသည္။ အားနည္းခ်က္မွာ လက္ရွိ ဗားရွင္းအတြက္ အသံုးျပဳနည္းအမ်ားစုကို အဂၤလိပ္ဘာသာျဖင့္ မရရွိႏို္င္ေသးျခင္းပင္ျဖစ္သည္။

####Open - Xchange

[Open - Xchange](http://www.open-xchange.com/home.html) သည္ ပုဂၢလိကပိုင္ 
အသင္းအဖြဲ႔ ေဆာ့၀ဲလ္ (MS - Exchange ကို အစားထိုးရန္ ရည္ရြယ္သည္) ျဖစ္ၿပီး ၎ကို အဖြဲ႔အစည္းပံုစံသစ္ျဖင့္ ထုတ္ေ၀ျခင္းကို စီးပြားျဖစ္ ဗားရွင္းေပၚတြင္ အေျခခံထားျခင္းျဖစ္သည္။ ေနာက္ဆံုး `.deb` package သည္ Hardy Heron 8.04 အတြက္ ျဖစ္သည္။ ၎သည္ အျခားေသာ clients မ်ား ျဖစ္သည့္ Kontact,Outlook,Palm PDAs မ်ားျဖင့္လည္း တြဲဖက္အသံုးျပဳႏုိင္သည္။ ျပည့္စံုေသာ တပ္ဆင္ပံုညႊန္ၾကားခ်က္မ်ားကို ၀က္ဘ္ဆိုဒ္တြင္ ေလ့လာႏုိင္သည္။

####Open Guoupware

[OpenGroupware](http://www.opengroupware.org/) သည္ postgre SQL ေဒတာေဘ့စ္အေပၚတြင္ အေျချပဳထားေသာ အစုအဖြဲ႔ ေဆာ့၀ဲလ္ ျဖစ္သည္။ ၎တြင္ စီးပြားျဖစ္ပံုစံႏွင့္ ပြင့္လင္းရင္းျမစ္ပံုစံ (၂၀၀၈ တြင္တိုးတက္မႈ ရပ္ဆိုင္းသြားသည္ )ရွိသည္။ အသစ္မထြက္ေတာ့ေသာေၾကာင့္ တပ္ဆင္မႈကို Source မွ တိုက္ရိုက္ ထည့္သြင္းရမည္။ အေသးစိတ္ကို ၀က္ဘ္တြင္ၾကည့္ပါ။

####Zarafa

[Zarafa](http:// zarafa.com/?q=en/content/community -O) သည္ ဥေရာပ၏ ဦးေဆာင္ MS-Exchange အစားထိုး အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္သည္။  ၎သည္ ယခင္က ပုဂၢလိကပိုင္ ၊ေနာက္ပိုင္း (မွတ္ပံုတင္အမွတ္မွလြဲ၍) GPL လိုင္စင္ျဖင့္ ပြင့္လင္းရင္းျမစ္ အဖြဲ႔အစည္းပံုစံကို ၂၀၀၈တြင္ ထုတ္လုပ္ခဲ့သည္။ ေဒါင္းလုပ္ ရယူႏုိင္သည့္ အခ်က္အလက္မ်ားကို ၀က္ဘ္ဆိုက္တြင္ ေဖာ္ျပထားသည္။

####Zimbra

[Zimbra](http://www.zimbra.com/downloads/os-download.html) သည္ ပုဂၢလိကပိုင္ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္ၿပီး (ယခု VMWare မွ ပိုင္ဆိုင္သည္ ) ပြင့္လင္းရင္းျမစ္ အဖြဲ႔အစည္းပံုစံကို ထုတ္ေပးထားသည္။ လက္ရွိတြင္အခမဲ့ေပးေသာ္လည္း အဖြဲ႔အစည္းပံုစံတြင္ ကန္႔သတ္ခ်က္မ်ားရွိၿပီး GPL လိုင္စင္မေပးေပ။ တင္သြင္းလိုက္ေသာ ေျပာင္းလဲမႈမ်ား၊ပါ၀င္ေရးသားမႈမ်ားသည္ VMWare ၏ ပိုင္ဆိုင္မႈမ်ားျဖစ္သြားသည္။  [Zimbra wiki](http://wiki.zimbra.com/wiki/Main-Page) ကိုၾကည့္ပါ။ Lucid Lynx 10.04 LTS အတြက္ ဘီတာဗားရွင္းကို ၆၄ဘစ္ အသံုးျပဳသူမ်ားအတြက္ ရရွိႏုိင္ၿပီး အေဟာင္း Hardy 8.04 ကိုလည္းအသံုးျပဳႏုိင္ပါသည္။

####School Tool

[School Tool](http://www.schooltool.org/) သည္ အေျခခံႏွင့္ အလယ္တန္းအဆင့္ ေက်ာင္းမ်ားအတြက္ ျပကၡဒိန္၊ ပညာရည္မွတ္တမ္း ၊ေက်ာင္းေခၚခ်ိန္ ၊ေက်ာင္းသား အခ်က္အလက္ သိမ္းဆည္းရာမ်ားအတြက္ ပြင့္လင္းရင္းျမစ္ အုပ္စုဖြဲ႔ေဆာ့၀ဲလ္ ျဖစ္သည္။ ၎ကို ဦးဘႏၱဳ မွ စပြန္ဆာေပးထားေသာ Shuttleworth ေဖာင္ေဒးရွင္း၏ အကူအညီျဖင့္ ဖန္တီးခဲ့ျခင္းျဖစ္သည္။တပ္ဆင္ရန္အတြက္ ညႊန္ၾကားခ်က္မ်ားကို ၾကည့္ပါ။ 

	[installation instructions](http://book.schooltool.org/htmlhelp/install.html)

####Sugar CRM Community Editon

[Sugar CRM](http://www.sugarcrm.com/crm/download) သည္ ေဖာက္သည္ဆိုင္ရာ စီမံခန္႔ခြဲမႈစနစ္ျဖစ္ၿပီးအေရာင္းအင္အားစုမ်ား (အေရာင္း ၊ေစ်းကြက္ျမွင့္တင္ေရး၊ ေထာက္ပံ့ေရး၊ စီမံခန္႔ခြဲမႈ ၊ အခ်ိန္ခြဲေ၀မႈမ်ား) အၾကားတြင္ ေပါင္းစပ္ညွိႏႈိင္းရာတြင္ သံုးေလ့ရွိသည္။ Sugar CRM အဖြဲ႔အစည္းပံုစံကို က်ယ္က်ယ္ျပန္႔ျပန္သံုးစြဲၾကသည္။ LAMP ဆာဗာကို ဦးစြာတပ္ဆင္သင့္သည္။ 

	sudo tasksel install lamp-server 

Sugar CRM ကို `/var/www` သို႔ ျဖည္ထုတ္ပါ။ ထို႔ေနာက္ http://localhost/SUGAR-FOLDER/ သို႔ Login ၀င္ပါ။ အျခားေရြးခ်ယ္စရာအျဖစ္ SugarCRM ဆာဗာအသစ္ကို LAMP ႏွင့္ 
ွSugarCRM အဖြဲ႔အစည္းပံုစံ အသင့္ပါၿပီး တပ္ဆင္ရန္ (ဘိုင္နာရီ) [instrallation](http://www.sugarcrm.com/crm/download#installers) ပံုစံျဖင့္လည္း ရႏိုင္ပါသည္။


####Guoupware Clients

အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္မ်ားသည္ Kontact/KMail/, Mozilla Thunderbird (သို႔) SeaMonkey တို႔ျဖင့္ ဆက္သြယ္မႈမ်ား ေဆာင္ရြက္ႏုိင္ၾကသည္။

####Evolution Exchange 

Evolution Exchange သည္ MS  Exchange 2000 2003 သို႔ (Outlook Web Access ) ကို အသံုးျပဳ၍ ဆက္သြယ္ႏုိင္သည္။ Install -

	sudo apt-get install evolution-exchange

####Kontact Personal Information Manager

Kontact Personal Information Manager တကုိယ္ရည္သံုး အခ်က္အလက္မန္ေနဂ်ာသည္ ဦးဘႏၱဳ တြင္တပါတည္းပါ၀င္ၿပီးျဖစ္ၿပီး အျခားေသာ အစုဖြဲ႔ ေဆာ့၀ဲလ္မ်ားျဖင့္ ေကာင္းစြာအလုပ္လုပ္ႏုိင္သည္။ interfaces with many [groupware servers](http://kontact.kde.org/groupwareservers.php).

####KDE Groupware Wizard

KDE အုပ္စုဖြဲ႔ေဆာ့၀ဲလ္ အလိုအေလ်ာက္ေဆာင္ရြက္မႈ  Kubuntu သည္ အလိုအေလ်ာက္ေဆာင္ရြက္မႈ (Script) ျဖင့္ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ဆာဗာႏွင့္ clients (Kontact/Kmail စသည္မ်ား ) ကို ဆက္သြယ္ႏုိင္ေစရန္ ကူညီေပးသည္။ ယခုလက္ရွိ ေထာက္ပံ့ႏို္င္ေသာ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္မ်ားမွာ Kolab, eGroupware, SUSE Linux Openexchange ႏွင့္ Novell Groupwise တို႔ျဖစ္ၾကသည္။

####Zimbra Desktop 

[Zimbra Desktop](http://www.zimbra.com/products/desktop.html) သည္ Zimbra ဆာဗာအတြက္အသံုးျပဳႏိုင္သည္။ Zimbra Desktop FQA မ်ား ကို ၾကည့္ပါ။ ပိုမိုသိရွိလိုပါက Ubuntu Forums Zimbra Desktop Installation [thread [1]](http://ubuntuforums.org/showthread.pmp?p=10634207)

####Oracle Calendar Desktop Client

[Oracle Calendar Desktop Client](http://www.oracle.com/technology/products/cs/user_info/ocalendar/desktop_index.html) သည္ oracle အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ ႏွင့္ ေဒတာေဘ့စ္ ႏွင့္ အသံုးျပဳရန္အတြက္ ပုဂၢလိကပိုင္ ျပကၡဒိန္ေဆာ့၀ဲလ္ ျဖစ္သည္။ Oracle Calendar Desktop Client ကို ေဒါင္းလုပ္ဆြဲရန္ 

	wget  http://ww.k_state.edu/infotech/calendar/oracle_10_clients/DesktopClients/Linux/callinu

ျဖည္ထုတ္ရန္ 

	tar_xvf cal_linux_1011.tar.gz

ျဖည္ထုတ္ၿပီးေသာ ဖိုင္မ်ားကို ဖိုလ္ဒါထဲသို႔ ေနရာေျပာင္းပါ။

	cd Cracle Calendar_inst/

ဖိုင္မ်ားကို ျပင္ဆင္ပါ။

	mv cal_linux cal_linux.bak; cat cal_linux.bak l seds/export LD_ASSUME-KERNEL/ #Xport LD_ASSUME_KERN

ခြင့္ျပဳမႈကို ျပင္ဆင္ပါ။

	chmod +x gui_install.sh cal_linux

GUI ျဖင့္ ထည့္သြင္းမႈကို စတင္ပါ။

	sudo sh gui_install.sh

--------------------------------

##အစုအဖြဲ႔ ျပကၡဒိန္မ်ား

###DAViCal Calendar Server

[DA Vi Cal](http://wiki. davical. org/ w/ Main_ Page) သည္ [CalDAV](http://en.wikipedia.org/wiki/CalDAV), postgre SQL, Apache php တို႔ကို အေျခခံထားၿပီး MozillaThunderbird/Lightning/Sunbird,Evolution ႏွင့္ အျခားေသာ ျပကၡဒိန္ client မ်ားျဖင့္ ေကာင္းစြာအလုပ္လုပ္ႏိုင္သည္။ install-

	sudo apt-get install davical

[အေသးစိတ္အခ်က္အလက္မ်ား](http://wiki.davical.org/w/Ubunty_Maverick)

###Darwin Calendar Server

[Darwin Calendar Server](http://trac.calendarserver.org/) ျပကၡဒိန္ ဆာဗာသည္ Apple ၏ [CalDAV](http://en.wikipedia.org/wiki/CalDAV ) ပြင့္လင္းရင္းျမစ္ port ကို အေျခခံထားေသာ ျပကၡဒိန္ဆာဗာ ျဖစ္ၿပီး  Mozilla Thunderbird/ Lightening/ Sunbird/ Evolution ႏွင့္ အျခားေသာ ျပကၡဒိန္ client မ်ားျဖင့္ ေကာင္းစြာအလုပ္လုပ္ႏုိင္သည္။ ရွင္း ၁.၂ ကို သိမ္းဆည္းထားေသာ ေနရာမ်ားမွ တပ္ဆင္ရန္မွာ (အေသးစိ္တ္ညႊန္ၾကားခ်က္မ်ားကို ၀က္ဘ္ဆိုက္တြင္ ၾကည့္ရႈပါ။ )

	sudo apt-get install calendarserver


###WebCalaendar

[WebCalaendar](http://www.k5n.us/webcalaendar.php?topic=About) သည္ [ICS](http://en.wikipedia.org/wiki/I Calendar) ကို အေျခခံထားေသာ အုပ္စုဖြဲ႔ ျပကၡဒိန္မ်ားအတြက္ ဆာဗာျဖစ္ၿပီး အမ်ဳိးမ်ဳိးေသာ ေဒတာေဘ့မ်ားျဖင့္ တြဲဖက္သုံးႏိုင္သည္။  PHP ျဖင့္ ေရးသားထားၿပီး Sunbird/Thunderbird
(Lightning) , Apple iCal, and Evolution ﻿စသည့္ clients မ်ားျဖင့္ တြဲဖက္သံုးႏိုင္သည္။ ေနာက္ဆံုးဗားရွင္းကို [RSS]( http://en.wikipedia.org/wiki/RSS ) clients သံုးကာ ၾကည့္ရႈႏိုင္သည္။ ေနာက္ဆံုး ဗားရွင္း (၁.၂) ကို တပ္ဆင္ရန္ ၀က္ဘ္ဆိုဒ္ ႏွင့္ [wiki](http://www.k5n.us/wiki/index.pmp?title=Main_Page)
ကို ၾကည့္ပါ။ ဗားရွင္းအေဟာင္း (၁.၀၅) ထည့္သြင္းရန္ 

	sudo apt-get install webcalendar

-------------------------------------

##Mail Servers

###Postfix/Dovecot (Mail Server)

[Postfix](http://www.postfix.org/) သည္ ပြင့္လင္းရင္းျမစ္ ေမးဆာဗာျဖစ္သည္။ ၎သည္ [Dovecot](http://www.dovecot.org/) , ပြင့္လင္းရင္းျမစ္ [IMAP](http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol) [POP3](http://en.wikipedia.org/wiki/Post_Office_Protocol) ဆာဗာမ်ားျဖင့္ တိုက္ရိုက္ခ်ိတ္ဆက္သည္။ ထပ္မံသိရွိလိုပါက official [Ubuntu documentation](http://help.ubuntu.com/11.04/serverguide/C/email_services.html) တြင္ ၾကည့္ပါ။ dovecot - postfix metapackage သည္ အစိတ္အပိုင္းမ်ား တပ္ဆင္ၿပီး Maildir (mail spooling) ဖိုလ္ဒါစနစ္ကို အသံုးျပဳႏိုင္ရန္အတြက္ ခ်ိန္ညွိမႈဆိုင္ရာ ဖိုင္မ်ားကို ျပဳျပင္သည္။ Imap and Pop3 မိုဂ်ဴး၊ SMTP ႏွင့္ SASL/TLS (သက္ေသခံလက္မွတ္ပါေသာ) မ်ားကို အလိုအေလ်ာက္တပ္ဆင္သည္။

	sudo apt-get install dovecot - postfix

###iRed Mail

[iRed Mail](http://code.google.com/p/iredmail/wiki/installation_on_Ubuntu) သည္ Dovecot, Postfix, a choice of Open LDAP (with phpLDAPAdmin) or MySQL ေဒတာေဘ့စ္၊
၀က္ဘ္အေျချပဳ ေမးလ္အတြက္  Roundcubemail or Squirrelmail ၊ phpAdmin, Postfix Admin, and A Wstats တို႔ကို ပါ၀င္ေသာ package ျဖစ္သည္။ ၎သည္ Lucid 10.04 LTS တြင္ အေကာင္းဆံုးျဖစ္ေစရန္စီမံထားၿပီး ဆာဗာအသစ္ေပၚတြင္ တပ္ဆင္ရန္ အေကာင္းဆံုးျဖစ္သည္။ (၎သည္ အီးေမးလ္ ဆိုင္ရာ ခ်ိန္ညွိမႈဖိုင္မ်ားစြာကို မူလအေနအထား ျဖစ္ေစရန္ ျပဳျပင္ေသာေၾကာင့္ျဖစ္သည္ ) ၎၏ အဖြဲ႔အစည္းပံုစံတြင္ စီးပြားျဖစ္ထုတ္လုပ္ေသာ ပံုစံ၏ အရည္အေသြးမ်ားစြာပါ၀င္သည္။

-----------------------------

##Financial Software

For a brief introduction, see this list of 10 Linux financial tools [here](http://ubuntudoctor.com/content/news/10-linux-financial-tools).

###KMyMoney (Personal Fiance Management)

[KMyMoney](http://kmymoney2.sourceforge.net/index-home.html) ကို ကၽြမ္းက်င္အေကာင့္ (Accountants) သမားေတြ အသံုးျပဳသလို အသံုးျပဳႏုိင္ပါသည္။ KMyMoney မွာလည္းပဲ MyMoney ႏွင့္ Intuit Quicken ကဲ့သို႔ ေငြစာရင္းေတြကို  double - accounting နဲ႔ အသံုးျပဳႏိုင္သလို၊ လုပ္ငန္းအတြက္လဲ သက္ဆိုင္ရာ အမ်ဳိးအစားအလိုက္ စီမံႏိုင္တဲ့ ေဆာ့၀ဲလ္ျဖစ္ပါသည္။ ကို KDE Kubuntu အတြက္ ျပဳလုပ္ထားတာျဖစ္ၿပီး Gnome/Ubuntu တို႕မွာလဲ သြင္းယူအသံုးျပဳႏို္င္ပါသည္။Install -

	sudo apt-get install kmymoney2

###Gnu Cash (Personal Finance Management)

[GnuCash](http://www.gnucash.org/) ဟာ အခမဲ့ေပးထားတဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ၿပီး GPL 
လိုင္စင္နဲ႔ အသံုးျပဳႏိုင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲ ျဖစ္ပါသည္။GnuCash မွာ ေငြစာရင္းေတြကို double-accounting နဲ႔ အသံုးျပဳႏုိင္သလို ကၽြမ္းက်င္အေကာင့္ (Accountants) သမားေတြကဲ့သို႔ အသံုးျပဳႏုိင္ပါသည္။ ကို GTK - based (Gnome 2) ကို အေျခခံၿပီး ျပဳလုပ္ထားျခင္းျဖစ္ပါသည္။အခု ေနာက္ဆံုးဗားရွင္းကို source files ကေန သြင္းယူလို႔ရေနပါၿပီ။ [Gnu Cash](http://www.gnucash.org/) မွာ ထည့္သြင္းမႈပံုစံေတြနဲ႔ ရႏုိင္တဲ့ ဗားရွင္းေတြကို ေတြ႔ရမွာျဖစ္ပါသည္။ Install-

	sudo apt-get install gnucash

###Skrooge (Personal Finance Management)

[Skrooge](http://skrooge.org/) ဟာ အခမဲ့ေပးထားတဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ၿပီး GPL လို္င္စင္နဲ႔ အသံုးျပဳႏိုင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲျဖစ္ပါသည္။ Skrooge ကို KDE ေတြမွာ အသံုးျပဳႏိုင္ေအာင္ ျပဳလုပ္ထားတာျဖစ္ၿပီး တျခား ေငြေၾကးစီမံခန္႔ခြဲမႈပရိုဂရမ္ေတြနဲ႔ တြဲၿပီး အသံုးျပဳႏုိင္ရန္အတြက္ ေဒတာေတြကို import/export လုပ္ႏုိင္တဲ့လုပ္ေဆာင္ခ်က္ ထည့္သြင္းေပးထားပါသည္။ Install -

	sudo apt-get install skrooge

###Moneydance (Personal Finance Management)

[Moneydance](http://moneydance.com/) ဟာ ကဲ့သို႔ စီးပြားျဖစ္ေရာင္းခ်တဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ပါသည္။ Java အား အေျချပဳ ဖန္တီးထားတာျဖစ္ၿပီး Operation System အမ်ဳိးမ်ဳိးအတြက္ အသံုးျပဳႏုိင္ေအာင္ ဖန္တီးထားတာျဖစ္ပါသည္။ အသံုးခ်ခြင့္လိုင္စင္အတြက္  တစ္ခုခ်င္းကို ေဒၚလာ ၅၀ ကုန္က်မွာျဖစ္ပါသည္။

###SQL - Ledger (Enterprise Fianance Management)

[SQL - Ledger ERP](http://www.sql-ledger.org/) က double-accounting စနစ္နဲ႔ အသံုးျပဳႏိုင္ၿပီး
Operation System မေရြးတဲ့ ၊ အခမဲ့ရရွိႏုိင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲျဖစ္ပါသည္။ ေနာက္ၿပီး SQL database server (PostgreSQL/Oracle/Mysql databases) ေတြကို အသံုးျပဳကာ inventory ,work and purchase orders,taxes ကဲ့သို႔ေသာ လုပ္ငန္းအခ်က္အလက္ေတြကို ခန္႔ခြဲႏိုင္တဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ပါသည္။ ကိုအသံုးျပဳမယ္ဆိုရင္ ၀ဘ္ဘေရာက္ဇာ (Internet exploer ,Mozilla Fox ) ကေနတစ္ဆင့္ အသံုးျပဳရမွာျဖစ္ပါသည္။ ကို က်ယ္ျပန္႔စြာ အသံုးျပဳႏုိင္ၿပီး ဘာသာစကားအမ်ားစုကိုလဲ အေထာက္အပံ့ေပးထားပါသည္။ Install -

	sudo apt-get install sql-ledger

--------------------------------------

##Wiki software

မျပင္ဆင္ရေသးပါ။ မၾကာမွီ ျပင္ဆင္မည္။

you can contribute

###Wiki 

software allows an organization to have a manual that can be edited by a number of collaborators.Wikipedia is the best known example.

###Media Wiki

[Media Wiki](http://www.mediawiki.org) is the free. မၾကာမီျပင္ဆင္ျဖည့္စြတ္မည္။

###Twiki

[Twiki](http://twiki.org) is an open source wiki engin used by many small to medium size companies internally. မၾကာမွီျပင္ဆင္ျဖည့္စြတ္မည္။

	sudo  apt-get  install   twiki


###Moin Moin

[Moin Moin](http://moinmo.in/) is free ,open source (GPL-Licensed) wiki မၾကမွီျပင္ဆင္ျဖည့္စြတ္မည္။

	sudo  apt-get  install  python-moinmoin

###Tiddly  Wiki

[Tiddly Wiki](http://www.tiddlywiki.com/)is an open source personal wiki. မၾကာမွီျပင္ဆင္ ျဖည့္စြတ္မည္။

-------------------------------

##Wed  Publishing

###Drupal (Web  content  publishing)

[Drupal](http://drupal.org/)သည္ website မ်ားဖန္တီးျခင္းႏွင့္ပူးေပါင္းေဆာင္ရြက္ျခင္းတို႕တြင္္ 
အသံုးျပဳေနၾကသည္႕tool  မ်ားထဲတြင္ ထိပ္ဆံုးမွရပ္တည္ေနသည္႕ open-source  တစ္ခုျဖစ္သည္။ရုိးရွင္းေသာ  website  မ်ားမွသည္အလြန္ရႈပ္ေထြးေသာ website မ်ားအထိ အခ်ိန္အနည္းငယ္ေပးေလ့လာရံုျဖင့္ ဖန္တီးေရးဆြဲႏို္င္သည့္ module အေျချပဳ wetside ဖန္တီးသည့္ toolျဖစ္သည္။ စတင္သံုးစြဲနည္းတြင္ သတင္းအခ်က္အလက္မ်ား စံုစံုလင္လင္ ရာယူႏို္င္ပါသည္။ Drupal အသံုးျပဳရန္အတြက္ LAMP server အား 
(Install မလုပ္ရေသးပါက Install ျပဳလုပ္ရန္လိုအပ္ၿပီး Drupal ႏွင့္ တပါတည္း Install  ျပဳလုပ္ႏုိင္ပါသည္။ Drupal ကို MySQL database (LAMP ရွိ M) ႏွင့္အလြယ္တကူ အသံုးျပဳႏုိ္င္ၿပီး PostgreSQL( Install 
ျပဳလုပ္ထားပါက ) ႏွင့္လည္း အသံုးျပဳႏုိင္ပါသည္။


####Drupal 17

Drupal 17 ၏ Debian package အား [ဤေနရာတြင္](https://packages.debian.org/sid/all/drupal7/) ရရွိႏုိင္ပါသည္။ သင့္ system (32 bit သို႔မဟုတ္ 64 bit) အတြက္ package အား download ျပဳလုပ္ကာ package
အား Synaptic သုိ႔မဟုတ္ Kpackage Kit စသည့္ package manager မ်ား အသံုးျပဳၿပီး  Install ျပဳလုပ္ႏုိ္င္သည္။ (K) Ubuntu OS အသစ္တြင္ တိုက္ရိုက္ Install ျပဳလုပ္ႏုိင္ရံုသာမက Debian respository ကိုပါ (Download
page တြင္ ေဖာ္ျပထားသည့္ လမ္းညႊန္ခ်က္အတိုင္း ) ထည့္သြင္းႏိုင္ၿပီး Install ျပဳလုပ္ႏို္င္သည္။

-Drupal6 မွ Drupal7 သို႔ေျပာင္းလဲရန္အတြက္ [ဤလမ္းညႊန္ခ်က္](http://drupal.org/node/570162) မ်ားအတိုင္း ျပဳလုပ္ႏို္င္ပါသည္။


####Drupal6 (Web content publishing)

Drupal6 အား package အျဖစ္ရယူႏိုင္ၿပီး  `command - line terminal` မွ လည္းရရွိႏိုင္သည္။

	sudo apt-get install drupal6

install ျပဳလုပ္ၿပီးပါက( ျဖစ္လာႏုိင္သည့္  ျပသနာအနည္းငယ္အား ေအာက္တြင္ေဖာ္ျပထားသည္ ) apache2
server အား restart ျပဳလုပ္ပါ။

	sudo/etc/init.d/apache2 restart

သင့္ browser မွတစ္ဆင့္ installation အား အၿပီးသတ္ေပးပါ။

	http://localhost/drupal6/install.php

Install ျပဳလုပ္ျခင္းအတြက္ သင့္ browser မွ တစ္ဆင့္ ဤ installation tips မ်ားအားဖတ္ရႈပါ။ ၿပီးေနာက္ Durpal site building tip မ်ားအား ၾကည့္ရႈပါ။ Drupal /Ubuntu အသံုးျပဳသည့္ Group အား Drubuntu တြင္
ေတြ႔ရွိႏုိင္ပါသည္။

####Installation quirks

	libgd 2- xpm

When I installed my Ubuntu server, it installed [libgd 2-noxpm
](http://package.ubuntu.com/jaunty/libgd2-noxpm). This is a graphics library without [X pixmap (XPM)](http://en.wikipedia.org/wiki/X_PixMap) or font configuration (fontconfig)
support). However, Drupal requires [libgd2-xpm](http://packages.ubuntu.com/jaunty/libgd2-xpm),which is used instead of libgd2-Xpm.Removing libgd 2-xpm doesn't appear to be trivial,
however.I could not remove it using apt,Adept,or KPackageKit.
 
However, Synaptic Package Manager does appear to remove libgd2-noxpm successfully,and
then libgd2-xpm can be installed.---

####Exim vs. Postfix

[Exim](http://www.exim.org/) ႏွင့္ [Postfix](http://www.postfix.org/) တို႔သည္ mail ထိန္းခ်ဳပ္သည့္ software မ်ားျဖစ္ပါသည္။ Drupal6 သည္ Exim ကို အသံုးျပဳထားသည့္အတြက္  Postifix အား install ျပဳလုပ္ထားပါက ျဖဳတ္ပစ္ၿပီး Exim ကို အသံုးျပဳထားသည့္အတြက္ Postfix ကို အသံုးျပဳထားေသာ 
mail server တြင္ Drupal6 အား အသံုးမျပဳပါက ပိုေကာင္းပါသည္။

###WordPress

[WordPress](http://wordpress.org/) သည္ အစပိုင္းတြင္ Blog ေရးရာတြင္ အသံုးျပဳသည့္ tool အျဖစ္မွ ေနာက္ပိုင္းတြင္ online စာေပေရးသားထုတ္ျပန္ရာတြင္ လိုအပ္သည့္ လိုအပ္ခ်က္မ်ားကိုပါ ေပါင္းစပ္ေပးထားေသာ လူၾကိဳက္မ်ားသည့္ open source web content manager တစ္ခုျဖစ္သည္။ Blogger မ်ားႏွင့္ website အေသးစားမွ အလယ္အလတ္ အရြယ္အစားမ်ားအတြက္ Wordpress မွ ျမန္ႏႈန္းျမင့္ install ျပဳလုပ္ျခင္းႏွင့္ module မ်ားျဖင့္ တန္ဆာဆင္ျခင္းမ်ားအား ေထာက္ပံ့ေပးထားပါသည္။ Wordpress အတြက္
LAMP server အား ဦးစြာ install ျပဳလုပ္ထားရန္လိုအပ္ပါသည္။ ထို႔ေနာက္ install လုပ္ရန္

	sudo apt-get install wordpress

-Wordpress ႏွင့္ တြဲဖက္အသံုးျပဳရန္အတြက္ သင့္ Apache2 ၏ www folder မွ install ျပဳလုပ္မည့္ 
folder သို႔ သေကၤတ link ျပဳလုပ္ရမည္ျဖစ္ၿပီး  Localhost အမည္ျဖင့္ MySQL database
အသစ္ေဆာက္ရန္ လိုအပ္မည္ျဖစ္ပါသည္။

	sudo in -s /usr/share/wordpress/var/www/wordpress
	sudo bash/usr/share/doc/wordpress/examples/setup-mysql -n wordpress local host

-မွတ္ခ်က္။ အကယ္၍ Wordpress အတြက္ သင့္ (virtual )host URL အမည္ကို သိၿပီးသားဆိုပါက 
localhost အစား သင့္ (virtual)host URL အမည္ကို ထည့္သြင္းပါ။

ဥပမာ သင့္ URL သည္ `mysite_x.homeserve.org` ျဖစ္သည္ဆိုပါစုိ႔ ။သင္ေရးရမည့္ command သည္ 

	sudo bash/usr/share/doc/wordpress/examples/setup-mysql-n wordpress mysite_x.homeserve.org

-အကယ္၍ virtual host တစ္ခုမွ သင့္ Wordpress server အားခ်ိတ္ဆက္လိုပါက `/etc/apache 2/site-available folder` တြင္ သင့္ virtual host အတြက္ configuration ဖိုင္တစ္ခု ဖန္တီးပါ။  ဖိုင္အား ဖန္တီးတည္းျဖတ္ၿပီးပါက ထိုဖိုင္မွ `/etc/apache 2/sites-enabled folder` သို႔ သေကၤတ link 
ျပဳလုပ္ေပးပါ။ Apache 2 အား restart ျပဳလုပ္ပါ။

	sudo/etc/init.d/apache 2 restart

Browser မွ တဆင့္ Wordpress အား Install ျပဳလုပ္ပါ။

	http://localhost/wordpress

သို႔မဟုတ္ သင့္ virtual host မွ တဆင့္ install

	http://mysite_x.homeserve.org/wordpress

-မွတ္ခ်က္။ Jaunty expositories တြင္ version 2.7.1 ပါရွိၿပီး Security Worm အျဖစ္သတ္မွတ္ ခံထားရပါမည္။ အကယ္၍ ထို version အား install ျပဳလုပ္ထားပါက Tools - Upgrade menu မွ လက္ရွိ version သို႔ ခ်က္ခ်င္း Update ျပဳလုပ္ေပးပါ။ (သို႔မဟုတ္ website မွတဆင့္ လက္ရွိ version အား install ျပဳလုပ္ပါ)

အလိုအေလ်ာက္ update ျပဳလုပ္လိုပါက Wordpress ၏ files မ်ားႏွင့္ Subfolder မ်ားကို www- data(apache 2 လုပ္ေဆာင္ခ်က္မ်ားအား ပိုင္ဆိုင္သည္) မွ update ျပဳလုပ္ရန္ ပိုင္ဆိုင္ရန္ လိုအပ္ပါသည္။

	sudo chown-R www-data/usr/share/wordpress


###Joomla (Web content publishing)

[Joomla](http://www.joomla.org/) သည္ website မ်ား ျပဳလုပ္ရာတြင္ ရိုးရွင္းသည့္ ပံုစံမ်ားမွ ရႈပ္ေထြးေသာ ပူးေပါင္းေဆာင္ရြက္မ်ားအထိ အသံုးျပဳႏိုင္ေသာ စြမ္းအားျမင့္ open source tool ျဖစ္သည္။ စတင္အသံုးျပဳရန္ [info for beginners](http://docs.joomla.org/Beginners) ကို ၾကည့္ရႈသင့္သည္။

---------------------------------

##Scribus (Desktop publishing)

[Scribus](http://www.scribus.net/) သည္ desktop publishing အတြက္ professional တစ္ခုအျဖစ္ အသံုးျပဳႏိုင္ေသာ open-source package တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install scribus

## Plone (Content Management System)

[Plone](https://plone.org/) သည္ ကမ ၻာအႏွံ႔ရွိ လုပ္ငန္းႀကီးမ်ားတြင္ အသံုးျပဳေနသည့္ content management system ျဖစ္ၿပီး platform မ်ဳိးစံုတြင္ အခမဲ့ အသံုးျပဳႏို္င္ေသာ open source (GPL - licensed ) system ျဖစ္သည္။ Installer ကို [ဒီေနရာ](http://plone.org/products/plone) တြင္ ရယူႏိုင္သည္။ Python ကို ေျပာင္းလဲထားေသာေၾကာင့္ အခ်ဳိ႕အသံုးျပဳသူမ်ားအေနျဖင့္ Jaunty တြင္ အခက္အခဲေတြ႔ႏိုင္ပါသည္။

##Gallery (Photo album website)

[Gallery](http://gallery.menalto.com/) သည္ PHP ကို အေျချပဳထားၿပီး ဓာတ္ပံု အယ္လ္ဘမ္မ်ားအား website တြင္ ျပသႏိုင္ေအာင္ ျပဳလုပ္ေပးသည့္ tool တစ္ခုျဖစ္သည္။ Drupal အတြက္ Gallery 2 Drupal interface အား ရရွိႏိုင္ပါသည္။ Install ျပဳလုပ္ရန္

[php BB (Forums) php BB](http://www.php BB.com/) သည္ Forum မ်ားတည္ေဆာက္ရန္ အသံုးျပဳသည့္ အခမဲ့ open source platform တစ္ခုျဖစ္သည္။ LAMP server (သို႔မဟုတ္) PostgreSQL database အား install ျပဳလုပ္ထားရန္ လိုအပ္သည္။ Install ျပဳလုပ္ရန္အတြက္ universe repositories အား enable ျပဳလုပ္ထားရန္ အထူးလိုအပ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install phpbb3

##Distance teaching

###Moodle

Moodle သည္ အြန္လိုင္း သင္ၾကားေရး cource မ်ား hosting ျပဳလုပ္ႏုိင္ရန္အတြက္ အခမဲ့ open source platform တစ္ခုျဖစ္သည္။ Webinar software ျဖင့္လည္း တြဲဖက္အသံုးျပဳႏိုင္သည္။ LAMP server အား Install ျပဳလုပ္ထားရန္ (sudo tasksel install lamp-server) လိုအပ္သည္။ Moodle ၏ အခမဲ့ theme မ်ားအား ဤေနရာတြင္ ရယူႏုိင္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get moode

Moodle အတြက္ Database server software (mysql-server-) ထည့္သြင္းလိုပါက ေဖာ္ျပပါ လမ္းညႊန္ခ်က္မ်ားအား လုပ္ေဆာင္ပါ။ Moodle အား ထည့္သြင္းထားသည့္ computer ေပၚတြင္ database အား တည္ေဆာက္၍ localhost option အား acept လုပ္ပါ။ လိုအပ္ပါက Moodle configuration အား တည္းျဖတ္ပါ။

	sudo gedit/etc/moodle/config.php

လုိအပ္ပါက `Moodle apache 2 configuration file` အား တည္းျဖတ္ပါ။

sudo gedit/etc/moodle/apache.conf

Browser မွတဆင့္ install ျပဳလုပ္ျခင္းအား အဆံုးသတ္ပါ။ (unattended install ျပဳလုပ္ျခင္းမွာ ပိုသင့္ေတာ္ပါသည္။)

`http://localhost/moodle/admin` 

စံုလင္စြာေလ့လာရန္အတြက္ အေသးစိတ္အခ်က္အလက္မ်ားတြင္ ၾကည့္ရႈပါ။

###Claroline

[Claroline](http://www.claroline.net/) သည္ e-learning course မ်ား hosting ျပဳလုပ္ရန္ႏွင့္ ေက်ာင္းသား/ေက်ာင္းသူမ်ား အြန္လိုင္းတြင္ ပူးေပါင္းလုပ္ေဆာင္ႏုိင္ရန္အတြက္ ျပဳလုပ္ထားသည့္ အခမဲ့ open-source platform တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္အတြက္ LAMP server အား install ျပဳလုပ္ထားရန္လိုအပ္သည္။ installation အတြက္ source file အား ၎ website တြင္ရယူႏိုင္ၿပီး လမ္းညႊန္ခ်က္မ်ားအား [ဤေနရာတြင္](http://www.claroline.net/documentation/tutorials.html) ေတြ႔ႏုိင္သည္။

###Dokeos

[Dokeos](http://www.dokeos.com/) သည္ အခမဲ့ သင္ၾကားေရး platform တစ္ခုျဖစ္ၿပီး ေဆးပညာဆိုင္ရာ ပံုမ်ား၊ case presentation မ်ားပါ ပါ၀င္သည္။ ဥေရာပတြင္ က်ယ္က်ယ္ျပန္႔ျပန္႔ အသံုးျပဳေနၾကပါသည္။

--------------------------------

##Software Development

###Kompozer Web Development Editor

[Kompozer](http://kompozer.net/) is a [Gecko](http://en.wikipedia.org/wiki/Gecko_(Layout_engine))

	sudo apt-get install kompozer

###Quanta Plus (Web IDE )

[Quanta Plus](http://quanta.kdewebdev.org/)

	sudo apt-get install quanta kompare kxsldbg cervisia

###Netbeans IDE

[Netbeans](http://www.netbeans.org/features/) is a free open-source

	sudo apt-get install netbeans

###BlueFish Web Development Editor

[BludFish](http://bluefish.openoffice.nl/) is a GTK-based (Gnome - oriented) editor to write websites,scripts and programming code. It supports perl, Python, pHp, CSS, XML , Java, Javascript, C, SQL , and other formats.

	sudo apt-get install bluefish

###Gobby ( Multi - user development)

[Gobby]( http://gobby.0x539.de/trac/) is a free, multi - platform open source collaborative editor supporting multiple documents in one session and a multi - user chat. Install:

	sudo apt-get install gobby

###Eclipse IDE

[Eclipse](http://www.eclipse.org/home/newcomers.php) is a free open - source cross - platform integrated development environment with plug in support for a large set of programming languages, e.g. Java,C/C++,Python ,PHP.

	sudo apt-get install eclipse

Science, Technology ,and Engineering Applications

What ..you thought Ubuntu was just for pay? Also see Ubuntu Science (http://help.ubuntu.com/community/OtherSoftware) . 

-----------------------------------

##Amateur Electronics

###Arduino

[Arduino](http://www.arduino.cc/) is an open - source electronics prototyping platform based on flexible, easy - to -use hardware and software. It's intended for artists, designer ,and bobbyists interested in creating interactive objects or environments.See [this tutotial](http://www.codetorment.com/2009/11/02/tutorial-getting-started-with-arduino-ide-on-linux-ubuntu-9-10/)

### La TeX

[La TeX](http://www.latex.project.org/) is a LaTeX is a free high- quality typesetting sytstem for the production of technical and scientific documention.

#### LyX

[LyX](http://www.lyx.org/) is a WYSIWYG frontend and GUI interface useful in creating documents formatted for La TeX. Install:

	sudo apt-get install Lyx


####La TeX Reference Managers

-The standard La TeX bibliography (Bib TeX) tool can be manipulated with one of several
tools:

-nbibtex. Install:

	sudo apt-get install nbibtex

-jabref. Install:

	sudo apt-get install jabref



-biblatex. Install:

	sudo apt-get install biblatex



-kbibtex (for KDE) .Install:

	sudo apt-get install kbibtex


-[Zotero](http://www.zotero.org) is a Firefox plugin that allows culling references (and reference content ) from online references.

--------------------------------------

##Utilities

Utilities facilitate everyday tasks, such as keeping the clock up to date, archiving utilities , and more.

###Archiving Utilities

####ZIP####

The command - line terminal utility [ZIP](http://linux.die.net/man/1/zip) creates files that are compatible with the time - honored PKZIP and WinZip. It is included in (K) Ubuntu by default.
Extracting zip files can be done with unzip utility.using the -P option allows using a 
password for the files.

	zip - r - p mypassword desination.zip

Notes: The -r option indicates to include all subdirectories recursively.

####FileRoller (Archiving GUI)

[FileRoller](http://fileroller.sourceforge.net/features.html) is a GUI for many types of archival utilities.

####X-archiver (Archiving GUI)####

[Xarchiver](http://xarchiver.sourceforge.net/) is a GTK - based GUI front -end for many archiving

utilities. Install:

	sudo apt-get install xarchiver

#### Rar

Rar archives files into the proprietary .rar format.

	sudo apt-get install rar

Note: This application is a 40-day trial.

####Unrar

Unrar extracts files archived with the proprietary .rar format. A free version can be installed:

	sudo apt-get install unrar-free

or the proprietary version (also free for noncommercial use) can be installed with the ubuntu-restricted-extras package or with:

	sudo apt-get install unrar

####7-Zip

The open-source 7-Zip archive format was originally designed for Windows (and DOS) but is also available for Ubuntu. The GNU/Linux version of  7-Zip does not come with a GUI, but Ark 
can hook into 7-Zip to handle 7z archives.Install:

	sudo apt-get install p7zip-full

To allow the 7-Zip extension for Ark to extract .rar files ,also install:

	sudo apt-get install  p7zip-rar

####Hard Drive Utilities

K Disk Free (Hard drive properties monitor)

[K Disk Free](http://docs.kde.org/stable/en/kdeutils/kdf/using-kdf.html) is a KDE utility for 
monitoring free disk space,etc.

	sudo apt-get install kdf



###Clock Utilties

####Screensavers

A screensaver is useful as a security precaution as well as a power and screen element saver.
Using even a simple Blank Screen screensaver with a password can slow a potentially malicious passerby from gaining access to your keyboard and computer while you are away from your 
desk.

	Menu - System - Preferences - Screen Saver

-Set a security password:

	Screen Saver - Lock screen when screensaver is active (ticked)

###Partition Managers

Also see these tips for partitioning scheme suggetions, other partitioning tools and methods, and usage of multiple partitions for multiple OSs.

####G Parted Partition Manager

[Gparted](http://gparted.sourceforge.net/) သည္ Hard Drive Partitions ခြဲရာတြင္ အသံုးျပဳႏိုင္ေသာ GTK(Gnome) အေျချပဳ ေဆာ့လ္၀ဲ တစ္ခုျဖစ္ပါသည္။ KDE တြင္လည္း အသံုးျပဳႏိုင္ပါသည္။

-ဤေဆာ့လ္၀ဲကို LiveCD ေပၚမွ အသံုးျပဳပါက အေကာင္းဆံုးျဖစ္ပါသည္။ ေနာက္ပိုင္းထြက္ရွိေသာ Ubuntu
LiveCD မ်ားတြင္ GParted ေဆာ့လ္၀ဲကို ထည့္သြင္းထားၿပီးျဖစ္သည္။ Ubuntu ကို စက္ထဲတြင္ Install
မလုပ္ဘဲ၊ CD မွ တိုက္ရိုက္ အသံုးျပဳၿပီး GParted ကို စတင္ႏုိင္ပါသည္။]

	Menu-System-Administration -GParted

-အျခားနည္းလမ္းတစ္ခုကား GParted .iso ဖိုင္ကို [ဤေနရာမွ](http://sourceforge.net/project/showfiles.php?group_id=115843package_id=271779) ရယူႏုိင္ပါသည္။ ထို .iso ဖိုင္ကို GPartet LiveCD ျပဳလုပ္ရန္ ဤ [CD Burning Guide](http://help.ubuntu.com/community/BurningIsoHowto) ကို ဖတ္ပါ။ G Parted LiveCD
ကို အသံုးျပဳၿပီး partitions ခြဲႏိုင္မည္ျဖစ္သည္။

-Ubuntu ကို Hard Drive အတြင္း  Install လုပ္ထားပါက Terminal တြင္ ေအာက္ပါ Command ကို ရိုက္ထည့္ၿပီး GParted ကုိ Install လုပ္ႏုိင္မည္ျဖစ္သည္။

	sudo apt-get install gparted


###System Backup and Recovery

####System Rescue and Cloning Utilities

#####System Rescue CD

[SystemRescueCD](http://www.sysresccd.org/Main_Page) is a LiveCD that includes important utilities such as GParted,Partimage,ddrescue, Rsync , and FSArchiver. Several of these utilities cannot be used from within a running partition, so using them from a LiveCD is often necessary.
[Download](http://www.sysresccd.org/Download) and [burn](http://help.ubuntu.com/community/BurningIsoHowto) the LiveCD from the website.


#####Clonezilla

[Clonezilla](http://clonezilla.org/)allows the backup or duplication of a partition for a single machine or for multiple machines over a network. (It is similar to North Ghost.)It includes
Partimage, [partclone](http://sourceforge.net/projects/partclone/),and other utilities.It is available [here](http://sourceforget.net/projects/clonezilla/files) as a LiveCD which can then be [burned](https://help.ubuntu.com/community/BurningIsoHowto).(A serious limitation of Clonezilla is
its inability to backup/restore split image files to/from multiple media (e.g.spanned DVDs/CDs),limiting its usefulness as an inexpensive cloning and distribution solution.Partition image
backup/restoration must be to/from a single hard drive,large capacity USB stick,or networked storage space)

####Disk Imaging software

[G4U](http://sourceforge.net/projects/g4u/) is a utility to image a disk bit by bit.

[G4L](http://sourceforge.net/projects/g4l/) is a  utility to image a disk bit by bit.It inkcludes a GUI interface.

#####Ubuntu Customization Kit

[Ubuntu Customization Kit](http://sourceforge.net/projects/uck) is a utility to customize a (K) Ubuntu LiveCD.Install:

	sudo apt-get install uck

####Remastering software

Debian and (K) Ubuntu Linux operating systems can be remastered and customized (using one of a number off utilities) for re-distribution.[See this Wikipedia list](http://en.wikipedia.org/wiki/List-of-rematering) for distribution among its members,while
preserving the intrinsic architecture and function of (K)Ubuntu.The customized (K) Ubuntu OS can than be distributed on a CD or a USB flashdrive. Users are then free to futher customize
the OS,or even to revent back to the original default(K)   settings. Also see the Ubuntu [wiki](http://help.ubuntu.com/community/InstallCDCustomization).

	oem-config-gtk

	sudo apt-get install oem-comfig-gtk

[Remastersys](http://sourceforge.net/projects/remastersys/Remastersys) for [Ubuntu](http://www.geekconneection.org/remastersys/ubuntu.html) .For tips, see this page. [Reconstructor](https://www.reconstructor.org/projects/reconstuctor/wiki/UserGuide). The open source engine can be [downloaded](https://www.reconstructor.org/projects/reconstutor/files) and installed a.deb package. 


***For tips,see this page.***

Run Ubuntu LiveCD from a USB pendrive

The Ubuntu LiveCD can be installed on and run from a USB pendrive. Settings ca be 
persistently saved (but the LiveCD kerned modules can not be upgraded). Programs can be
installed and run,however ,and files saved to the USB drive. (The installed programs will remain
installed). An Ubuntu Live CD is needed to do the installation. For additional info, see the [Ubuntu Community documentation](http://help.ubuntu.com/community/Installation/FromUSBStick) or the [Pendrivelinux instructions](http://www.pendrivelinux.com/creating-an-ubuntu-live-usb-from-cd/).

The USB LiveCD can be used to install Ubuntu on computers (including netbooks) that do not
have CD-ROM/DBD drives.

USB pendrives to be used to run Ubuntu should have a minimum of 2 Gb(preferably 4 Gb).If
you wish to install a fast, fully functional Linux system on a pendrive that has less memory than
that, use [PuppyLinux](http://www.puppylinux.org/) or [Lubuntu](https://wiki.ubuntu.com/Lubuntu).

###USB Creator##

You can make a LiveCD on a USB pendrive using USB Creator and either a LiveCD or an .iso
version of the LiveCD stored on your hard drive. USB Creator is installed by default in Ubuntu.
If not,install:

	sudo apt-get install usb-creator-gtk

-Run:

	Menu-System-Startup Disk Creator

Create a boot CD to allow booting from the USB drive

Many computers do not allow booting from a USB drive (but they do allow booting from the CD-ROM). You can create a CD-ROM using these [Pendrivelinux instrctions](http://www.pendrivelinux.com/make-a-usb-boot-cd-for-ubuntu-9-10/)  and set your BIOS to boot from this CD-ROM. When you boot from this CD-ROOM, it will use the bootup files on the Ubuntu USB drive you previously created (in the step above).

--------------------------------------

##System Administration##

###GRUB boot manager settings

####Grub2

Ubuntu 11.04 (Natty) တြင္ boot manager အျဖစ္ (customize လုပ္ရန္ ရႈပ္ေထြးေသာ) [Grub2](http://www.gnu.org/software/grub/maunal/grub.html) ပါလာပါသည္။ (Grub2 ႏွင့္ grub-pc သည္ 
တစ္မ်ဳိးတည္းသာ ျဖစ္သည္။) Grub2 အတြက္ ညႊန္ၾကားခ်က္မ်ားကို [Ubuntu wiki](http://wiki.ubuntu.com/Grub2) သို႔မဟုတ္ [Ubuntu forums](http://ubuntuforums.org/showthread.php?t=1195275) မ်ားတြင္ ၾကည့္ရႈႏုိင္သည္။ အၾကမ္းအားျဖင့္

	sudo nano /etc /default /grub
	sudo grub-mkconfig--output=/boot/grub/grub.cfg


အျခားေသာနည္းလမ္းအေနျဖင့္ ေအာက္ပါ command ကို အသံုးျပဳႏိုင္သည္။

	sudo update-grub


####Turn off ACPI through GRUB

The new Linux kernel , starting with Karmic ,will attempt to throttle the CPU every few seconds
based on lm-sensors read of CPU temperature and fan speed. If your hardward is not supported
by lm-sensors (like mine), this will cause your system to show down dramatically or even freeze.
As always, this is an ACPI problems, so disabling it at boot often takes of the problem.Edit
the GRUB configuration as above and add the line:

	GRUB _ CMDLINE _ LINUX =acpi=off


Grub2 background image,colors,fonts

-Grub2 အတြက္ ေနာက္ခံပုံရိပ္မ်ား၊ အေရာင္မ်ား ၊ Font မ်ား [ဤေနရာတြင္](http://ubuntuforums.org/showthread.php?p=10720685#post10720685) ၾကည့္ပါ။

-Grub2 တြင္ မည္သည့္ ေနာက္ခံပံုကို သံုးသည္ျဖစ္ေစ အသံုးျပဳမည့္ပံုကို `/boot/grub` ဖိုင္တြဲတြင္ ထည့္၍ Grub2 ကို configure လုပ္ျခင္းျဖင့္ အသံုးျပဳႏုိင္သည္။

	sudo update grub

အသံုးျပဳမည့္ပံုသည္ `/etc /default /grub` တြင္ ရွိသည့္ Grub 2 စတင္လုပ္ေဆာင္ရန္ သတ္မွတ္ထားေသာ
ပံုအရည္အေသြးႏွင့္ တူညီရမည္။ (ဥပမာ 1024 x 768)

-ေရြးခ်ယ္ထားေသာ splashimage မ်ားကို `/usr/share/image/grub` ဖိုင္တြဲတြင္ ထည့္သြင္း၍ 
  အသံုးျပဳႏိုင္သည္။

	sudo apt-get install grub2-splashimages

-အသံုးျပဳလိုေသာ ပံုရိပ္တစ္ခုကို `/boot/grub` ဖို္င္တြဲတြင္ ထည့္၍ splashimage အေနျဖင့္အသံုးျပဳႏိုင္သည္။ ဥပမာ

	sudo in -s /usr /share /images /grub /Plasma-lamp.tga/boot/grub
	sudo update-grub

####Grub 2 အား ခ်ဳိးေဖာက္၀င္ေရာက္ျခင္း မျပဳႏုိင္ရန္ ကာကြယ္ျခင္း

-Grub2 ကို ကာကြယ္ရန္ အေရးႀကီးေသာ အခ်က္မ်ားကို [Grub Manual](http://www.gnu.org/software/grub/manual/grub.html#Security ) တြင္ ၾကည့္ပါ။

-စကား၀ွက္ထည့္သြင္းရန္အတြက္ /etc/grut.d/40_custom configuration file တြင္ ေအာက္ပါ command ကို ရိုက္ထည့္ပါ။
	set superusers=user1
	password_pbkdf2 user1 grub.pbkdf2.sha512.10000.biglongstring
	password user1 insecurecleartextpassword


စကား၀ွက္ေနရာတြင္ insecurecleartextpassword အစား သင္၏ စကား၀ွက္ ထည့္သြင္းအသံုးျပဳရပါမည္။
သို႔မဟုတ္ [ဤေနရာ](http://www.gnu.org/software/grub/manual/grub.html#Security) တြင္ ျပထားေသာ pbkdf2-encrypted နည္းလမ္းကို အသံုးျပဳ၍ ကာကြယ္ႏုိင္သည္။ သင္၏ Ubuntu OS Grub2 လံုျခံဳေရးႏွင့္ ပတ္သက္၍ အေသးစိတ္ကို ဤ [Blog](http://www.panoet.com/set-grub-2-password-protection-149) တြင္ ဖတ္ရႈႏိုင္သည္။

####GRUB Legacy

Boot partition တစ္ခုႏွင့္ အသံုးျပဳရန္ GRUB ၏ version အေဟာင္းျဖစ္သည့္ (Grub [Legacy](http://www.gnu.org/software/grub/manual/legacy/grub.html) ကို ရယူႏုိင္သည္။ Grub Legacy ကို ထည့္သြင္းရန္အတြက္

	sudo apt-get install grub

-အကယ္၍ သင့္ကြန္ပ်ဴတာတြင္ operation system တစ္ခုထပ္ပိုရွိေနပါက multiple operation systems (OS) ျဖစ္ေနၿပီး သင္သည္ Grub Legacy boot manager ကို သံုးစြဲဖူးၿပီး ျဖစ္ေကာင္းျဖစ္ႏုိင္သည္။ Grub Legacy ၏ option မ်ားကို menu.1st configuration file တြင္ တည္းျဖတ္ျပင္ဆင္ႏုိင္သည္။ အေသးစိတ္ကို ၾကည့္ရႈႏိုင္သည္။

	sudo nano /boot /grub /menu.1st

(text editor အျဖစ္ nano အစား gedit ကို အသံုးျပဳႏိုင္သည္။)

####Grub Legacy မွ data မ်ား ရယူ၍ Grub2 တြင္ ျပန္လည္ အသံုးျပဳျခင္း

Grub Legacy မွ data မ်ားရယူ၍ Grub2 တြင္ အသံုးျပဳရန္အတြက္ Grub Legacy ၏ menu.1st configuration file တြင္ ဤပံုစံျဖင့္ မိမိ OS မ်ားကို ျဖည့္သြင္းပါ။ (menu.1st ဖိုင္ကို boot partition တြင္ သိမ္းဆည္းထားသည္။)

	title Kubuntu Maverisk OS (chainloader)
	rootnoverity (hdo,6)
	kernel /boot /grub /core.img

သို႔မဟုတ္

	title Kubuntu Maverick OS (chainloader)
	rootnoverify  (hdo,6)
	configfile/boot/grub.cfg


####Grub Legacy ကိုခ်ိဳးေဖာက္၀င္ေရာက္ျခင္းမျပဳႏုိင္ရန္ ကာကြယ္ျခင္း

-Grub Legacy ကိုကာကြယ္ရန္ အေရးၾကီးေသာအခ်က္မ်ားကို this section of [the Grub Manual](http://www.gnu.org/software/grub/manual/legacy/grub.htm#Security) တြင္ ၾကည့္ပါ။

-စကား၀ွက္ထည့္သြင္း ကာကြယ္ရန္အတြက္ `/boot/grub/menu.1st` configuration file တြင္ ေအာက္ပါ  command line ကို uncomment လုပ္ပါ (hash သေကၤတကို ဖယ္ထုတ္ပါ။)

####password topsecret

ထို႔ေနာက္ စကား၀ွက္ထည့္သြင္း၍ သို႔မဟုတ္ [ဤေနရာ](http://www.gnu.org/software/grub/manual/legacy/grub.html1#Security ) တြင္ ျပထားေသာ md5-
encrypted နည္းလမ္းကို အသံုးျပဳ၍ ကာကြယ္ႏုိင္သည္။ menu item မ်ားကို စကား၀ွက္ျဖင့္ ကာကြယ္ရန္ မည္သည့္ item menu ၏ ေခါင္းစဥ္ေအာက္တြင္မဆို ကာကြယ္ထားေၾကာင္း အမွတ္အသားျဖစ္သည့္ lock ကို 
ထည့္သြင္းျခင္းျဖင့္ လုပ္ေဆာင္ႏိုင္သည္။

###Default Applications###

Ubuntu ၏ ယခင္ version မ်ားတြင္ သင္ သတ္မွတ္ထားေသာ လုပ္ငန္းမ်ားအတြက္ မည္သည့္ program အား ပံုေသအသံုးျပဳမည္ကို သင့္အေနျဖင့္ ဤေနရာမွ ေရြးခ်ယ္ႏို္င္သည္။

	Menu-System-Administration-Default Applications

(သို႔မဟုတ္) 

ဖိုင္တစ္ခုအား right-click' ႏွိပ္၍  `Open with Other Application` ျဖင့္လည္း ေရြးခ်ယ္ႏုိင္သည္။

Default Application menu သည္ လက္ရွိ Ubuntu version တြင္ မပါရွိေတာ့ပါ။ သို႔ေသာ္ ဤ function အား ျပဳလုပ္ခြင့္ေပးေသာ GUI ႏွင့္ Ubuntu ႏွင့္ Multiple similar Ubuntu system twesk မ်ားအတြက္ 
[UbuntuTweak](http://ubuntu-tweak.com/) ကို install ျပဳလုပ္၍ အသံုးျပဳႏိုင္ပါသည္။

	wget http://launchpad.net/ubuntu-tweak/0.5.x/0.5.8/+ download/ubuntu-tweak_0.5.8-1all.deb
	sudo dpkg -i ubuntu- tweak _ 0.5.8-1_all.deb


###Kill a process###

တစ္ခါတစ္ရံမွာ Program တစ္ခု (သို႕မဟုတ္) process တစ္ခုဟာ အသံုးျပဳေနစဥ္မွာပဲ ရပ္တန္႔ (hang)သြားတတ္ပါတယ္(ဥပမာ Firefox)။ထိုကဲ႔သို႔ေသာ program (သို႔မဟုတ္) process မ်ားအား kill (သို႕မဟုတ္) ပိတ္ပစ္ရန္အတြက္
	
Menu-System-Administration-System Monitor-highlight the errant process-Kill process

မွပိတ္ႏိုင္ပါတယ္။

command line မွလည္း

	sudo killall process 

ဟုရိုက္ကာ ပိတ္ႏိုင္ပါတယ္။ process ေနရာတြင္ ရပ္တန္႕ေနေသာ program ( firefox ဆိုပါက firefox) ဟုထည့္ေပးရပါမယ္။

-------------------------

###Enabling NUM LOCK On Startup###

Menu-System-Administration-Keyboard Mouse-Keyboard-turn on Numlock on Startup


###Working with Menus#


###Create an encrypted folder###

သင့္အေနျဖင့္ encrypted  ျပဳလုပ္ထားသည့္ အရာမ်ားပါ၀င္ေသာ folder တစ္ခု ဤလမ္းညႊန္ခ်က္မ်ား 
(http://help.ubuntu.com/community/EncryptedPrivatedDirectory) အား ၾကည့္ရႈ၍ ဖန္တီးႏိုင္ပါသည္။

Create a symlink from a file to another location

[symbolic link](http://en.wikipedia.org/wiki/Symbolic_link) (သို႔) symlink ဟုလည္း သိၾကသည့္ သေကၤတလင့္သည္ Linux ၏ file သုိ႔မဟုတ္ directory တစ္ခုအား တစ္ေနရာမွ အျခားေနရာသို႔ ညႊန္ျပသည့္ နည္းလမ္းတစ္ခုျဖစ္သည္။ 
အသံုးျပဳပံု

	Ln -s /path /to /source/path/to/destination

အကယ္၍ `/path/to/destination` မွ `superuser` ျဖစ္ရန္လိုအပ္ပါက ေအာက္ပါ command အား အသံုးျပဳပါ။

	sudo Ln-s /path /to/source /path/to/destination

ဤနည္းသည္ ယခင္ window user မ်ား အကၽြမ္းတ၀င္ရွိၾကမည့္  Shoutcut မ်ားဖန္တီးသည့္ ပံုစံျဖင့္ ဆင္တူေသာ္လည္း ပို၍ အဆင့္ျမင့္ (စြမ္းအားျမင့္) ပါသည္။


###Assign a root password###

Root သုိ႔ တို္က္ရိုက္ `log in`  ျပဳလုပ္ႏိုင္ရန္အတြက္  root password ထည့္သြင္းေပးရန္လိုအပ္ပါသည္။ password ထည့္သြင္းရန္အတြက္ 

	sudo passwd rood

ထို႔ေနာက္ သင့္အေနျဖင့္ `su` ကို အသံုးျပဳ၍ root သုိ႔သြားပါ။ ထုိ႔ေနာက္ root password အား ထည့္သြင္းေပးပါ။


###root password မရွိပဲ root permission အသံုးျပဳျခင္း။###
Get a root prompt without using a root password
 
root password ကုိ မထည့္ရေသးလွ်င္ျဖစ္ေစ၊ ေမ့ေလ်ာ့သြားရင္ျဖစ္ေန ေအာက္က ကြန္မန္းေတြ သံုးျပဳျပီး root access ရယူႏုိင္ပါတယ္။

	sudo - s
	
or

	sudo su

or

	sudo bash

ဒါဆိုရင္ root password သံုးမယ့္အစား လက္ရွိသံုးေနတဲ့အေကာင့္ရဲ ့password ကုိပဲသံုးျပဳသြားပါလိမ့္မယ္။ တျခား user အေကာင့္ေတြကုိလဲ ေအာက္က ဥပမာအတုိင္း ေခၚသံုးႏုိင္ပါတယ္။

	sudo su username

File Manager ကုိေအာက္က command ေတြအသံုးျပဳျပီး root access နဲ့ဖြင့္ႏုိင္ပါတယ္။

	sudo nautilus
	
or

	gksudo nautilus


Device ေတြ ျဖဳတ္တပ္ကို maunal ျပဳလုပ္ဖုိ့အတြက္ေအာက္က ကြန္မန္းသံုးပါတယ္။

	mount /dev/hda

`hda` ေနရာမွာ ကုိယ္ mount လုပ္ခ်င္တဲ့ဟာကုိ အစားထိုးရမွာပါ။

unmount ျပဳလုပ္ဖုိ့အတြက္က ေအာက္က ကြန္မန္းသံုးျပဳပါတယ္။

	umount/dev/hda

`hda` ေနရာမွာ ကုိယ္ mount လုပ္ခ်င္တဲ့ဟာကုိ အစားထိုးရပါတယ္။။

-------------------------------------------------

##Networking##

တစ္ခုတည္းေသာ Network manager အား GUI interface ျဖင့္ စတင္လုပ္ေဆာင္ေစႏိုင္ပါသည္။ Network-Manager သည္ ပံုမွန္အေနျဖင့္ ပါ၀င္ၿပီးျဖစ္သည္။ သို႔ေသာ္လည္း အသံုးျပဳသူမ်ားသည္ [Wicd Network Manager](http://wicd.sourceforge.net/)  ကို ပို၍ ႏွစ္သက္ၾကသည္။


###Network Manager

Network Manager သည္ ubuntu တြင္ ပံုမွန္အေနျဖင့္ ထည့္သြင္းထားၿပီးျဖစ္သည္။ ၎သည္ Notification 
ေနရာတြင္ internet connections (wireless APs သို႔မဟုတ္ wired connection တို႔ကို )ခ်ိတ္ဆက္ရန္ သို႔မဟုတ္ အသံုးမျပဳရန္ ေရြးခ်ယ္ႏုိင္ပါသည္။


###Wicd Network Manager###

[Wicd Network Manager](http://wicd.sourceforget.net/) is a GTK -dependent networking manager written in Python that can be used in all variants of Ubuntu. Many users (including me) report it 
to be faster and more stable than Network Manager. To avoid networking conflicts, Wicd
requires the removal of Network Manager prior to installation.

	sudo apt-get remove network-manager
	sudo reboot
	sudo apt-get install wicd


###Set a static IP address###

I have never been able to ger Network Manager to accept my static IP address settings. If you 
only use only a wire interface, you do not neekd a network manager and it can be removed.

-Remove Network Manager:

	sudo apt-get remove network-manager
	sudo reboots

-Edit the /etc /network/interfaces files:


###GPPP###

GPPP သည္ ယခင္ Ubuntu versions ေတြရဲ႕  default modem dailing application ျဖစ္ခဲ့ပါသည္။

`Menu` - `Applications` - `Internet` - `GPPP Internet Dail` - 
`up Remote Access`

Remote Access နည္းလမ္းမ်ဳိးစံုရွိပါသည္။ VNC Sharing ကို သံုးျခင္းျဖင့္ ရီမုတ္လုပ္ထားေသာ ကြန္ပ်ဴတာ၏ Desktop ကို ၾကည့္ႏိုင္၊ ထိန္းခ်ဳပ္ႏုိင္ပါသည္။ (Windows သံုးသူမ်ားသည္ အလားတူ `(remote desktop
protocol,RDP )` ဟု ေခၚေသာ သီးျခားအဖြဲ႔အစည္း တစ္ခုပိုင္ ပရိုတိုေကာကို သံုးၾကသည္။) `XDMCP (X Display Manager Control Protocol)` ျဖင့္ လည္း` X-windows` ကို အေျခခံသည့္ ၿပီးျပည့္စံုေသာ Remote Login ကို ျပဳလုပ္ႏိုင္ပါသည္။ ခြင့္မျပဳသင့္ေသာ ၀င္ေရာက္ျခင္းမ်ား ၊ေဒတာအခ်က္အလက္ ပို႔ေဆာင္ျခင္းမ်ားကို 
ကာကြယ္ေပးေသာ သင့္ေတာ္သည့္ ၾကိဳတင္ကာကြယ္မႈမ်ားမရွိလွ်င္ `Remote Connection` သည္ လံုျခံဳေရးအရ အႏ ၱရာယ္ရွိေပသည္။ 

###SSH###

`Secure Shell` သုိ႔မဟုတ္ `SSH` လို႔ေခၚေသာ  network protocol တစ္ခုျဖစ္ပါသည္။ ၎ Protocol သည္ ကြန္ပ်ဴတာ ႏွစ္ခုၾကားတြင္ `Secure channel` (သို႔မဟုတ္ tunnel ) မွ တဆင့္ အခ်က္အလက္ေတြကို ဖလွယ္ႏိုင္ရန္ 
အေထာက္အပံ့ေပးပါသည္။ Encryption လုပ္ျခင္းျဖင့္ သတင္းအခ်က္အလက္မ်ားကို တိက်လံုျခံဳမႈ ရွိေစပါတယ္။

OpenSSH client ကိုေတာ့ Ubuntu တြင္ default အေနနဲ႔ install လုပ္ထားၿပီး အျခား `SSH server run` ေနေသာ ကြန္ပ်ဴတာတစ္ခုႏွင့္ ခ်ိတ္ဆက္ေပးႏုိင္မွာျဖစ္ပါတယ္။

------------------------------------------

##Tips Tricks##

###Run Command###

Run Command အသံုးျပဳျခင္း သင့္ရဲ႕ စက္အတြင္းက  Application မ်ားကို Run Command မွတဆင့္ အသံုးျပဳႏုိင္ပါတယ္။ `Alt + 2` ကိုသံုးပါ။

###Hot Keys မ်ားအား ပိတ္ျခင္း###

ကၽြန္ေတာ့အျမင္မွာေတာ့ ဒါဟာ အလြန္အႏ ၱရာယ္ရွိတဲ့ လုပ္ေဆာင္ခ်က္တစ္ခုျဖစ္ပါတယ္။။ အစက္ေလးတစ္စက္ဟာ
ထင္မွတ္မထားတဲ့ ဘယ္လို အျဖစ္အပ်က္မ်ဳိးကို မဆုိ ျဖစ္သြားေစႏိုင္ပါတယ္။ စိတ္မေကာင္းစရာအျဖစ္န႔ဲပဲ ဒါဟာ ျပသနာတစ္ခုအျဖစ္နဲ႔ Operation System ထဲမွာ ရွိေနၿပီး  turn off လုပ္ဖုိ႔လည္း ခက္ခဲပါတယ္။

`Menu` - `System` - `Administration` - `Advanced` - `Input Actions` - `General Settings` - `check` to`Disable KHotKeys daemon`

`Menu`- `System` - `Administration` - `Advanced` - `Input Actions` - `Gestures Settings` -
		`check` to  `Disable mouse gestures globally`

တကယ္လို႔သင္က `Disable mouse gestures globally` ကို ေရြးခ်ယ္ခ်င္ပါတယ္ဆိုရင္ေတာ့  (တခါတရံမွာ အလုပ္မလုပ္ပါ) Desktop ေပၚက မလိုအပ္တဲ့ Hotkey ေတြကို disable လုပ္ပါ။

`Menu` - `System` - `Administration` - `Advanced` - `Keyboard Mouse` - `Keyboard Shortcuts`

ၿပီးေတာ့ သင္က linking gestures to sticky and slow keys ကို deactivate လုပ္ခ်င္တယ္ဆိုရင္ေတာ့

`Menu` - `System` - `Administration` - `Accessibility` - `Activation Gestures` - `uncheck` to - `Use
	gestures for activating sticky keys and slow keys`

မွတ္ခ်က္။     ။ သင့္အေနနဲ႔ application အေတာ္မ်ားမ်ားကို အသံုးျပဳမယ္ဆိုရင္  hotkeys ေတြကို `disable` လုပ္ထားရပါမယ္။

`Synaptic Touchpad` မွ `hotkeys` မ်ားကေတာ့ 
[Ubuntu documentation](https://help.ubuntu.com/community/Synaptics/Touchpad#Ubuntu) ကို အသံုးျပဳၿပီး ေရြးခ်ယ္
	turned off ျပဳလုပ္ႏိုင္ပါတယ္။

###Associate default applications###

သက္ဆိုင္ရာ application မ်ားအား အလိုအေလ်ာက္ပြင့္ရန္

-Dvd player အလိုအေလ်ာက္ပြင့္လာရန္အတြက္ DVD playback လုပ္ေဆာင္ႏိုင္စြမ္းကို ဖြင့္ထားရန္လိုအပ္ပါသည္။ ပထမဦးစြာ
	
`Menu` - `System` - `Administration` - `Advanced` - `File` `Associations` - x - content - video - dvd - `Applications Preferance order` - `Add` တြင္ မိမိႏွစ္သက္ရာ media player အား ေရြးခ်ယ္ပါ။ ၎တြင္ Blu - Ray ႏွင့္ HD DVD 	အတြက္ ဆင္တူေသာ  ေရြးခ်ယ္မႈဇယားရွိပါသည္။ တစ္ခုခ်င္းစီအား ေရြးခ်ယ္သတ္မွတ္ေပးပါ။

-`MPEG` ႏွင့္ အျခား ရုပ္သံ `Format` မ်ားအတြက္ အလိုအေလ်ာက္ player မ်ားသတ္မွတ္ရန္
	
`Menu` - `System` -`Administratio`n - `Advanced` - `File Associations` - `video` -`mpe`g -`Applications Preference order - Add` တြင္ သင့္စိတ္ၾကိဳက္  `media player` ကို ေရြးခ်ယ္ပါ။ .wmv) x -ms -wmv, သို႔မဟုတ္ Microsoft ၏ WMV format) ,.flv (x-flv, သို႔မဟုတ္ Flash video ), quicktime စသည္ ရုပ္သံဖိုင္ေပါင္းမ်ားစြာအတြက္ လက္ခံဖြင့္ႏုိင္မည့္ player အားေရြးခ်ယ္အသံုးျပဳႏုိင္ပါသည္။

-Audacious မွတဆင့္ .pls အသံ stream မ်ားကို သတ္မွတ္ေပးရန္အတြက္ Audacious:

`Menu` - `Syste`m - `Administration` - `Advanced` -`File Associatons` - `audio` - `x` -`scpls` -
	`Applications Preference order` - `Audacious` အား အေပၚဆံုးသို႔ ေရႊ႕ေျပာင္း၍ (သို႔မဟုတ္)ထည့္ေပးျခင္းျဖင့္ လုပ္ေဆာင္ႏုိင္ပါတယ္။

Filename Patterns Section ထဲတြင္ေတာ့ `* .pls`  ရွိေနရန္လုိအပ္သည္။

###User စကား၀ွက္အသံုးျပဳရန္ မလိုပဲ ၀င္ေရာက္ေသာစနစ္###

သြားေရာက္ျပင္ဆင္ရန္အတြက္ (မွတ္ခ်က္ ၊ User အတြက္ password လိုအပ္ေနဆဲျဖစ္ပါသည္။ )

`Menu` - `System` -`System Settings` -`Login Manager` -`Convenience` - `Enable Auto` - `Login`	(အမွန္ခ်စ္) - `Lock session` (အမွန္ခ်စ္) -`Pre` - select user: `Specified :Choose primary user`

-ဒါကို ျပဳလုပ္ရင္ေတာ့ screensaver ကို Password - Portected နဲ႔တြဲၿပီး လုပ္သင့္ပါတယ္။


###Program မ်ားအား bootup လုပ္စဥ္ အလုိအေလ်ာက္စတင္ေစျခင္း

မည္သည့္ program မဆို `~/.config/autostart folder` သုိ႔ program သေကၤတ
လမ္းေၾကာင္း ဖန္တီးေပးျခင္းအားျဖင့္ `bootup` ၌ စတင္ေစလိုပါက သေကၤတလမ္းေၾကာင္း ဖန္တီးေပးရပါမည္။

	sudo in -s /usr/bin/firefox ~/.config/autostart


###Bootup /Startup service မ်ားေရြးခ်ယ္ျခင္း

System ၏ လုပ္ေဆာင္ခ်က္မ်ား တိုးတက္ေစရန္အတြက္ Startup ျပဳလုပ္စဥ္တြင္ မလုိအပ္ေသာ/ 
အသံုးမျပဳလိုေသာ service မ်ား စတင္ျခင္းမ်ား မျဖစ္ေအာင္ ကာကြယ္ရပါမည္။

-GTK အား အေျချပဳထားေသာ Bootup - Manager အား Install ျပဳလုပ္ရန္

	sudo apt-get install bum

	
###Bootup-Manager အား အသံုးျပဳရန္#
	 
`Menu` - `System` - `Bootup` - `Manager` 


###Menu item မွ Script အား အသံုးျပဳျခင္း##

(password စသည့္ )တံု႔ျပန္ေမးခြန္းမ်ား ေမးျမန္းျခင္းမ်ားအား ေျဖဆိုရန္ script တိုေလးမ်ားအား Menu item ထဲတြင္ ထည့္သြင္းႏိုင္ပါသည္။ ေအာက္တြင္ SSH Negotiation ျပဳလုပ္စဥ္ password ထည့္ေပးႏိုင္သည့္ ဥပမာအား ေဖာ္ျပေပးထားပါသည္။ ပထမဦးစြာ အသံုး၀င္  [expect](http://linux.die.net/man/1/expect) program အား install ျပဳလုပ္ပါ။

	sudo apt-get install expect

Menu item တြင္ shortcut (သို႔) command အသံုးျပဳျခင္း ျဖစ္ပါသည္။ 

ဤ password ဥပမာသည္ ssh program မွ password လိုအပ္ေသာအခါ sshpassword ကို သြားေစပါသည္။
Expect သည္ command-line terminal မွ စာလံုးအခ်ဳိ႕ကိုေစာင့္ဆိုင္း ရယူၿပီး စာမ်ားျပန္ထုတ္ေပးသည္။
ထို႔ေၾကာင့္ Menu Iten ကို terminal တြင္သာ run   ေစရမည္ျဖစ္္္္္္သည္။


###[SHC](Encrypt scripts)

[SHC](http://www.datsi.fi.upm.es/~frosal/) သည္ code ႏွင့္ password စသည္မ်ားကို မျမင္ေအာင္ ျပဳလုပ္ေပးၿပီး ထို script မ်ားကို binary အျဖစ္သို႔ ေျပာင္းလဲေပးသည့္ ရိုးရွင္းေသာ script compiler တစ္ခုျဖစ္သည္။ အသံုးျပဳပံုမ်ားအား ဤေနရာတြင္ (http://www.datsi.fi.upm.es/~frosal/sources/shc.html) ၾကည့္ရႈႏိုင္ပါသည္။ `Debian Etch respository` ကို ထည့္သြင္းျခင္းျဖင့္ install ျပဳလုပ္ႏိုင္ပါသည္။

	sudo add-apt-repository http://archive.debian.org/debian/etc main

ထို႔ေနာက္ shc package အား install ျပဳလုပ္ပါ။

	sudo apt-get install shc

###Capture a screenshot 

Screenshot ျပဳလုပ္ျခင္း ဤ [Tutorial](http://tips.webdesign10.com/how-to-take-a-screenshot-on-ubuntu-linux) တြင္ ၾကည့္ပါ။


###Desktop အား KDE  ကဲ့သို႔ ေျပာင္းလဲျခင္း

ေနာက္ဆံုးထြက္ Ubuntu ဗားရွင္းတြင္ Gnome desktop အား ျပဳျပင္၍ cleaner KDE desktop အျဖစ္ ျပင္ဆင္ႏုိင္ပါသည္။ (ျပဳျပင္ျခင္းသည္ အလြန္ ကိုယ္ေရးကိုယ္တာက်သျဖင့္ ဤအပိုင္းသည္ လမ္းညႊန္အျဖစ္သာ ေဖာ္ျပေပးထားသည္။ )

`-Desktop Customization ျပဳျပင္ျခင္းကို ၾကည့္ပါ။`

###Ubuntu တြင္  KDE 4 Desktop အသံုးျပဳျခင္း

Kubuntu တြင္ အလိုအေလ်ာက္ပါၿပီးျဖစ္ေသာ KDE4 အေျချပဳ Desktop အား Ubuntu တြင္ install လုပ္ႏုိင္ပါသည္။

	sudo apt-get  install kubuntu-desktop

KDE4 အား install လုပ္ရာတြင္ အသံုးမလိုေသာ feature မ်ားျပားျခင္းႏွင့္  Module  မ်ားအၾကား လိုက္ေလ်ာညီေထြမႈမရွိျခင္း ျပသနာမ်ားၾကံဳေတြ႔ရတတ္ပါသည္။ Login ျပဳလုပ္ရာ၌ KDE (Kubuntu) Desktop ျဖင့္ ျဖစ္ေစ၊ Gnome (Ubuntu) Desktop ျဖင့္ျဖစ္ေစ၊ ႀကိဳက္ႏွစ္သက္ရာျဖင့္ ျပဳလုပ္ႏုိင္သည္။ သို႔ေသာ္လည္း Desktop တစ္ခုခ်င္းစီမွ Modules ၂ခုသည္  function တစ္ခုအား လုပ္ေဆာင္မည္ဆိုပါက
အခက္အခဲ(ကြဲလြဲျခင္း)မ်ား ျဖစ္ႏိုင္ပါသည္။

###KDE 3 Desktop အား Ubuntu  တြင္ အသံုးျပဳျခင္း

သင့္အေနျဖင့္ ယခင္ Lucid (သို႔မဟုတ္) မည္သည့္ KDE 3 application မွ KDE 3 Desktop ကို Ubuntu တြင္
install လုပ္ႏုိင္ပါသည္။	

-ေဖာ္ျပပါ KDE 3 repositories အား ထည့္ပါ။

	sudo add-apt-repository ppa:kde3-maintainers

-KDE 3.5 desktop အား install လုပ္ပါ။

	sudo apt-get update
	sudo apt-get install kubuntu-desktop-kde3

-မည္သည့္  KDE 3 application ကိုမဆို install ျပဳလုပ္လိုပါက package အမည္တြင္  `-kde3` ဟူေသာ	 စာလံုးကို ထပ္ျဖည့္ေပးရပါမည္။ အခ်က္အလက္ အျပည့္အစံုအတြက္ [Pearson Computing](http://apt.pearsoncompution.net/) ကို ၾကည့္ပါ။


###Kill (end) a process 

Process (application) အား ပိတ္ျခင္း (သို႔မဟုတ္) အဆံုးသတ္ျခင္း

-Frozen PC ကို ျပင္ဆင္ရန္ နည္းလမ္းအေတာ္မ်ားမ်ား ရွိပါသည္။ `Alt + F2` ကို ႏွိပ္ပါ။ ထို႔ေနာက္  frozen Application ကို ပိတ္ရန္ Killall ကို အသံုးျပဳပါ။ 

ဥပမာ:

	sudo killall amarok
	sudo killall firefox

-ထစ္ေနေသာ Graphic ႏွင့္ ဆိုင္သည့္ application မ်ားကို ပိတ္ရန္အတြက္ `xkill utility` ကို သံုးပါ။`Alt+F2` ကို ႏွိပ္ပါ။ `xkill` ဟု ရိုက္ၿပီး run ကို ႏွိပ္ပါ။  သင္ပိတ္လိုေသာ  application ေပၚတြင္ Mouse ၏ ၀ဲလက္ခလုတ္ကို ႏွိပ္ပါ။ 

ဤနည္းျဖင့္  သင္ပိတ္လိုသည့္ application မ်ားကို ပိတ္ႏိုင္ပါသည္။

###skill

-အျခားနည္းအေနျဖင့္ `AltGr+SysRq+K (Right Alt +Print Screen + K)` ကို ႏွိပ္ပါ။ ဒီနည္းက သင့္ကို logout ျဖစ္ေစမွာျဖစ္ပါတယ္။ တကယ္လို႔ ဒီနည္းက အလုပ္မျဖစ္ဘူးဆိုရင္ေတာ့  `Ctrl + Alt + F1` ကိုႏွိပ္ၿပီး login လုပ္ပါ။ ၿပီးေတာ့ သင့္ password ကို ႏွိပ္ၿပီး run ပါ။

	sudo killall gdm
	sudo startx


###View hidden files 

Hidden File မ်ားအား ၾကည့္ရႈျခင္း  Nautilus Manager မွာ ဒါေလးကို ႏွိပ္ပါ။

	ctrl + H

###Notification (အခ်က္ျပျခင္း ) ေတြကို အသံေဖ်ာက္ရန္

-အခ်က္ေပးသံေတြကို disable ျပဳလုပ္ဖို႔အတြက္

	Menu - System - Preferences - Sound -Sound Effects - Sound 	theme: -No sounds - Close

-GNOME အခ်က္ေပးခ်က္ေတြဟာ အသံျဖင့္ အလိုအေလ်ာက္ ဆက္စပ္ေနပါတယ္။ ဒါကို သီးျခား disable ျပဳရပါမယ္။
	
`Alt - F2 - gconf - editor -/apps/indicators - sound - volume _mute` (အမွန္ျခစ္ေပးပါ။ )

-Login အခ်က္ေပး အသံကို ပိတ္ရန္အတြက္

`Menu - System -Preferences - Startup Applications - Startup Programs - GNOME LoginSound` (အမွန္ ျခစ္ျဖဳတ္ေပးပါ။ ) 

`-Menu - System - Administration - Login Screen - Unlock - Play login sound` (အမွန္ျခစ္ျဖဳတ္ေပးပါ။)

###Random password generator

က်ပန္း password geneartor

	-Pwgen သည္ က်ပန္း password စာလံုးစုမ်ားထုတ္ေပးရန္အတြက္  အသံုး၀င္သည့္ command line
	တစ္ခုျဖစ္သည္။ Kubuntu တြင္ Konsole မွ တဆင့္ ၊Ubuntu တြင္ Terminal မွတဆင့္
အသံုးျပဳႏိုင္သည္။ Install ျပဳလုပ္ရန္ ----

	sudo apt-get install pwgen

-Pwgen အား အသံုးျပဳရန္
	
	pwgen

-UUIDgen သည္ က်ပန္း UUID မ်ားအား ထုတ္ေပးသည့္ အသံုး၀င္ေသာ
	အလိုအေလ်ာက္ ထည့္သြင္းေပးထားသည့္ program တစ္ခုျဖစ္သည္။ အသံုးျပဳရန္ း
uuidgen


ဆႏၵရွိပါက က်ပန္း UUID အား password အေနျဖင့္လည္း အသံုးျပဳနိုင္ပါသည္။


###Password chceker and enforcement

[John the Ripper](http://www.openwall.com/john/) Password စစ္ေဆးမႈႏွင့္ အတည္ျပဳမႈ

John the Ripper သည္ Dictionary ၏ password မ်ားအား ဖ်က္ရန္အတြက္ အခမဲ့အသံုးျပဳႏိုင္ေသာ open source ျဖစ္ၿပီး ေယဘုယ်အားျဖင့္ ၄သန္းခန္႔ ဘာသာေပါင္းစံုျဖင့္ အသံုးျပဳေနၾကသည္။ အဘယ္ေၾကာင့္ဆိုေသာ္
ဤ program သည္ က်ယ္က်ယ္ျပန္႔ျပန္႔ႏွင့္ လြယ္လင့္တကူ ရႏိုင္ေသာေၾကာင့္ ျဖစ္ၿပီး  မိမိ၏ ကြန္ျပဴတာ ႏွင့္ LAN ၏  password မ်ားအား  စစ္ေဆးျခင္း၊ လံုျခံဳေအာင္ ျပဳလုပ္ျခင္းမ်ားအတြက္လည္း ၏
အသံုး၀င္ေသာေၾကာင့္ျဖစ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install john

[Passwdqc](http://www.openwall.com/passwdqc/) သည္ password မ်ား၏ ၾကံ့ခိုင္မႈအားအတည္ျပဳေပးရန္အတြက္ သံုးေသာ module တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install passwdqc


###MD5Sum###

File တစ္ခု၏ MD5 sum မ်ားအား စစ္ေဆးရန္အတြက္ သံုးေသာ command line တစ္ခုျဖစ္သည္။

	md5sum filename

မွတ္ခ်က္။  ။ Filenames with spaces

###Spaces ခံ၍ အမည္ေပးထားေသာ File မ်ား###

-`Spaces` ခံ၍ ရိုက္ႏွိပ္ထားေသာ File ႏွင့္ Folder အမည္မ်ားအား မ်က္ေတာင္ အဖြင့္ အပိတ္မ်ား `( )` မ်ား ထည့္အသံုးျပဳသင့္သည္။ ဥပမာအားျဖင့္ This Dir အမည္ေပးထားေသာ directory တစ္ခု သို႔မဟုတ္
	`/home/This Dir` အမည္ရွိ directory တစ္ခုအား ေျပာင္းလဲခ်င္ပါက ေအာက္ပါ command 
	အား အသံုးျပဳရမည္။

	cd This Dir

သုိ႔မဟုတ္

	cd/home/This Dir

-တစ္နည္းအားျဖင့္ `backslash (/)` ကို space ေနရာမွာ အစားထုိးျခင္းျဖင့္လည္း အသံုးျပဳႏုိင္ပါသည္။

This Dir အမည္ေပးထားေသာ directory တစ္ခု သို႔မဟုတ္ `/home/This Dir` အမည္ရွိ directory တစ္ခုအား ေျပာင္းလဲခ်င္ပါက 

	cd This /Dir 

သို႔မဟုတ္

	cd/home/This /Dir


###Alien###

[Alien](http://kitenet.net/~joey/code/alien/) သည္ (Red Hat) .rpm packages မ်ားကို  (Debian).deb packages မ်ားအျဖစ္သို႔ ေျပာင္းလဲေပးေသာ ဖိုင္ေျပာင္းနည္းတစ္ခုျဖစ္သည္။ ဒီနည္းဟာ စိတ္ခ်ရတဲ့နည္းမဟုတ္သလို ေျပာင္းလိုက္တဲ့ package ေတြရဲ႕ function ေတြကို ေသခ်ာျပန္စစ္ေဆးေပးဖို႔လိုအပ္ပါတယ္။ မ်ားေသာအားျဖင့္ စာေၾကာင္းေတြ ျပန္ေျပာင္းေပးဖို႔ လိုအပ္ပါတယ္။ Source ကေန `(Debian).deb package` ကို ေျပာင္းေပးျခင္းက ပိုၿပီးစိတ္ခ်ရပါတယ္။ Alien software ရဲ႕ maintainer ေတြ ကို္ယ္တိုင္ကိုက important package ေတြကို ဖိုင္ေျပာင္းတဲ့အခါ Alien ကို အသံုးမျပဳေစခ်င္ၾကပါဘူး။ Alien ကို version နံပါတ္ေတြ ေျပာင္းတာကေန ထိန္းထားခ်င္တယ္ဆိုရင္ေတာ့ ေဖာ္ျပပါ command ကို ရိုက္ထည့္ေပးပါ။

	alien - k rpm _file _name.rpm

.rpm ကို .deb အျဖစ္ေျပာင္းနည္း

	alien - d package - name .rpm

.rpm ကို .deb အျဖစ္ေျပာင္းၿပီး ရလာတဲ့ file ကို တစ္ခါတည္း install လုပ္ရန္

	alien - i package - name .rpm

.rpm ကို Debian အျဖစ္ေျပာင္းရန္

	sudo alien - k  .rpm
	
--------------------------------

##Software Troubleshooting##

###Program အစတြင္ လုပ္ပိုင္ခြင့္ Error တက္ျခင္း

အကယ္၍  သင့္တြင္ လုပ္ပိုင္ခြင့္ Error တစ္ခုတက္လာပါက ေဖာ္ျပပါအတိုင္း လုပ္ေဆာင္ပါ။

	sudo chown - R user /home/user

မွတ္ခ်က္ ။    user ဆိုေသာ ေနရာတြင္ သင့္ username အမွန္အား ထည့္ေပးပါ။ ဤ command သည္ folder ၏ ပိုင္ရွင္အား ေျပာင္းလဲေပးမည္ျဖစ္သည္။ `-R` အပါအ၀င္  (recursively ) ကိုဆိုလိုၿပီး folder အခြဲမ်ားပါ ပါ၀င္ပါသည္။


##CD - ROM Troubleshooting##

###CD - ROM Error အားေျဖရွင္းျခင္း###

အကယ္၍ သင္ CD burner အသံုးျပဳၿပီး  burn ေန႔စဥ္အတြင္းမွာ `cdrecord has no permission to open the device` ဆိုတဲ႔ Error တက္လာပါက terminal ကို ဖြင့္ၿပီး

	sudo chmod 777 /dev /scd0

လို႔ ရိုက္လိုက္ပါ။

မွတ္ခ်က္။ `/dev/scd0` ေနရာတြင္ သင့္ device အားထည့္ေပးပါ။
မွတ္ခ်က္။ `chmod 777` သည္ folder အား လုပ္ပိုင္ခြင့္အျပည့္အစံုေပးလိုက္သည့္ universal option ျဖစ္သည္။ `777` ဆုိေသာ ဂဏန္းသည္ ေရးျခင္း၊ ဖတ္ျခင္း ၊လုပ္ေဆာင္ျခင္း စသည့္ လုပ္ပိုင္ခြင့္ တု႔ိကို အသံုးျပဳသူအား အျပည့္အ၀ ေပးလိုက္သည္ဟု အဓိပၸါယ္ ရသည္။

