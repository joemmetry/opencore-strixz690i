# Intel Z690-I チップセット + Intel Raptor Lake Refresh CPU OpenCore EFI

### [English](https://github.com/joemmetry/opencore-strixz690i/blob/master/README.EN.md)

OpenCore ブートローダー用の EFI フォルダー。[OpenCore Vanilla デスクトップガイド](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)にて作成されました。

<img src = "https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.6435-9/206743122_10216513288344107_3539624459220602424_n.jpg?_nc_cat=109&_nc_rgb565=1&ccb=1-3&_nc_sid=0debeb&_nc_ohc=GIahA9UCavwAX-0qNjY&_nc_ht=scontent.fmnl17-2.fna&oh=26a8b3847e6d7f8eaf644a7e4826a00f&oe=60F11940" />

### 特徴

- 最新 macOS 14.5 のサポート
- GUI ブートメニューは有効
- トリプルブート（macOS、Windows、Ubuntu）
- Bootcamp は機能します

### ソフトウェアバージョン

- macOS Sequoia 15.5 (24F5042g)
- Windows 11
- Ubuntu 24.04
- OpenCore 1.0.5

### システムコンポーネント

| **コンポーネント** | **モデル**                             |
| ------------------ | -----------------------------------------------|
| CPU                | Intel Core i5 14600K                           |
| マザーボード         | ASUS ROG Strix Z690-I Gaming Wi-Fi             |
| RAM                | 64GB (32+32GB) OLOy Blade 5 @ 6400MHz          |
| オーディオ           | Realtek ALC4080 Codec                         |
| GPU                | Sapphire Nitro+ AMD Radeon RX 6950 XT 16GB     |
| Wi-Fi と Bluetooth | Broadcom BCM94360CS2                           |
| イーサネット         | Intel Ethernet Controller i225-LM              |
| OS ディスク（SSD）   | Western Digital Black SN850X 1TB               |

### 動作可能

CPU、RAM、ファン、クーリングなど ✔<br/>
オーディオ ✔<br/>
イーサネット ✔<br/>
グラフィック ✔<br/>
HDMI ✔<br/>
スリープ/ウェイク機能 ✔<br/>
電力管理 ✔<br/>
App Store ✔<br/>
iMessage ✔<br/>
iCloud ✔<br/>
FaceTime ✔<br/>
USB ✔<br/>
ブートローダー ✔<br/>
HDMI オーディオ ✔<br/>
ボリュームホットキー ✔<br/>
Wi-Fi ✔<br/>
Bluetooth ✔<br/>
ハンドオフ ✔<br/>
AirDrop ✔<br/>
Docker（Docker マシンのみが機能） ✔<br/>

### 動作不可能

サイドカー ✗<br/>

### クイックノート

1.カーネル拡張機能および　OpenCanopy　のリソースはこのリポジトリに含まれていません。[acidanthera](https://github.com/acidanthera)、およびその他のプロバイダーにアクセスして、最新のバージョンをダウンロードしてください。<br/>
2.Apple のサポートは制限されているために機能しない macOS ものがいくつかあります。 <br/> 3.このリポジトリは、独自の EFI を構成する方法を学習するためのものです。これをコピーして、EFI パーティションに配置するだけでは、システムが正常に起動されません。<br/>

### ソース

- [OpenCore インストールガイド](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Vanilla OpenCore](https://github.com/AMD-OSX/AMD_Vanilla)
- [OpenCore EFI および Kexts](https://dortania.github.io/builds/)
