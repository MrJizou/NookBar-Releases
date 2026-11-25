# Kablosuz pil protokolleri: kaynaklar

NookBar'ın kablosuz cihaz pil okuyucuları (`src/wireless_battery.cpp`, `src/wireless_vendors.cpp`) bu
projeye özgü koddur. Cihaz protokollerine dair bilgi (rapor biçimleri, komut baytları, yanıt konumları) aşağıdaki
topluluk projelerinin belgelerinden ve incelemelerinden öğrenildi. Kod kopyalanmadı. Emekleri için teşekkürler.

- Wireless Device Battery Monitor (krisgfx9): https://github.com/krisgfx9/Wireless-Device-Battery-Monitor
  (sürücü listesi ve protokol özetleri; aşağıdaki kaynakları bir araya getiren proje)
- Solaar / Logitech HID++ 2.0 belgeleri: https://github.com/pwr-Solaar/Solaar
- LGSTrayBattery (G HUB yerel servisi ws://localhost:9010 protokolü): https://github.com/andyvorld/LGSTrayBattery
- HeadsetControl: https://github.com/Sapd/HeadsetControl (Logitech kulaklık gerilim → yüzde kalibrasyon noktaları dahil)
- OpenRazer: https://github.com/openrazer/openrazer
- rivalcfg (SteelSeries): https://github.com/flozz/rivalcfg
- HyperHeadset (HyperX Cloud III S vb.; Cloud Flight gerilim eşik tablosu): https://github.com/LennardKittner/HyperHeadset
- HyperXWM (HyperX Cloud III Wireless): https://github.com/Medprj/HyperXWM
- BatteryTray (Rongyuan / Xenta 2.4G alıcıları, Akko vb.): https://github.com/qu1ncky/BatteryTray
- Linux hid-playstation (DualShock 4 / DualSense rapor düzeni)
- inzone-buds-battery-tray (kinako19, takamachi66): Sony INZONE
- glorious-indicator, glorious-ctl: Glorious
- Linux hid-kysona (Lode Willems), PulsarBattery, HaloBattery, mouse-battery: Kysona / Pulsar / ATK
- m913-ctl, redragon-m913-battery-tray: Areson (Redragon M913)
- G-Wolves, LAMZU, Hitscan web yapılandırıcıları
- Galaxy Buds çerçeve biçimi: GalaxyBudsClient topluluğu
- Endgame Gear: johanneszab/vole, Janlhin/Endgame_Gear_Web_Configurator
- ZOWIE: yleshchuk/zowie-battery, IgnacioBarb/zowie-battery-tray
- ASUS ROG: SteveWang92/peripheral-battery-tray, 1gcat/BatteryTool, G-Helper; Pelta: jimm0thy/pelta-control, B1Chat/BatteryWatch
- Keychron: Keychron Launcher, nvalis/nape_pro, gtun/KeychronNapeBatteryWidget, ky0209/NapeBar
- SONiX (AJAZZ/AULA): donglover69/sonix-keyboard-studio
- Rapoo: Rapoo Hub, PyFlat/Device-Battery-Info
- MCHOSE: alexfrih/mchose-linux, Jstdi001/MCHOSE-Monitor, MCHOSE M HUB
- Ninjutso: NinjaForce yapılandırıcısı; DAREU / MCHOSE alıcıları: wushuai0802/myfinder-device-battery
- AULA klavyeler: PyFlat/Device-Battery-Info, deepan-alve/womier-l65-linux, ushineko/sanshoku
- Cooler Master: syntactic-spice/coolermaster-usb-protocol, riVFerd/MM731-Controller
- Fractal Scape: Fractal Adjust Pro; Jabra: Watchdog0x/jabridge
- GameSir: WWWyyy452/GamesirBatteryTray, AJAY0406/Gamesir-Nova-2-Lite-Battery-Detection, vdemonchy/cyclone2-linux
- Flydigi: SDL hidapi_flydigi; Steam Controller: Linux hid-steam
- Fantech: jarjut/xd5-go-web, libratbag; JBL Quantum: JBL QuantumENGINE; MOONDROP: jeromeof/devicePEQ
- Royal Kludge: RK web sürücüsü; Sprime: sprime.pro web sürücüsü; VAXEE: stuffz/mouse-battery-monitor
- Motospeed: Jacobz888/LGSTrayBattery-MotospeedX6; Xenta / Delux: AeonArcHQ/omarchy-delux-m900
- AJAZZ: Rockeyxx/aj179-linux, Aiacos/ajazz-control-center, werquess/ajazz-aj139-macos, nico2525nn/AjazzAJ139V2
- Incott: OmarK6/Incott-Manager, HeHaoren/incott-mouse-app, FelixNg21/MouseBattery; Wraith W1: w1.software web sürücüsü
- ATK: HeyOkay/HaloBattery, qwr79/mouse-battery, ATK HUB
- Logitech G435 (0ADF): portyporty/g435-battery-percentage, deddroid/logitech-g435-battery
- Razer BlackShark V3 / V3 Pro (FF14, 64 bayt): HeyOkay/HaloBattery#292 ve openrazer/openrazer#2794 (Synapse USB yakalaması, çerçeve + uyandırma dizisi)
