# XOXO Version 1.0.5
XOXO merupakan auto bash/shell script yang bisa digunakan untuk play video, download video, download mp3, edit/render video, live stream, generate kode, play/record tv.

## Fitur
- [x] Play Video (Local Disk, Youtube, Vidio)
- [x] Download Video (Youtube, Vidio, Facebook, Instagram)
- [x] Download Mp3 Youtube
- [ ] Upload Video (*belum tersedia)
- [x] Live Stream (Youtube, Facebook)
- [x] Bypass Copyright Video
- [ ] Input Kode (*belum tersedia)
- [ ] Generate Kode (*belum tersedia)
- [x] Play TV
- [x] Record TV

## Alat yang wajib diinstall (khusus windows)
- Git for windows >> https://git-for-windows.github.io/
- Python 3 ke atas >> https://www.python.org/downloads/windows/
- Ffmpeg (Linking pilih shared) >> https://ffmpeg.zeranoe.com/builds/

## Instalasi utama
Jalankan command berikut pada git bash, di folder yang diinginkan, cek video tutorial di https://www.youtube.com/watch?v=iPdawz6GqAY
- `git clone -b master https://github.com/nurd1n/Xoxo`

Atau bisa juga download file zip langsung : https://github.com/nurd1n/Xoxo/archive/master.zip

## Instalasi tambahan
- Windows : jalankan file install_windows.sh
- Linux :
-- berikan permission file : `chmod 755 *.sh`
-- ubah dos to unix : `sed -i 's/\r$//' *.sh`
-- jalankan file install_linux_ubuntu.sh

## Cara menjalankan
Klik 2 kali file `xoxo.sh` , atau juga bisa masukkan command `./xoxo.sh` pada git bash atau terminal jika menggunakan linux

## Update
Untuk update, buka git bash here di folder xoxo, kemudian masukkan command `git pull` dan `git submodule update --init --recursive` pada git bash

## Credits
- [Youtube-dl](https://github.com/rg3/youtube-dl)
- [Youtube-upload](https://github.com/tokland/youtube-upload)
- [Ffmpeg](https://ffmpeg.org/)

## Contributors script
- [Nurdianto](https://www.facebook.com/nurdiantocyk)
- [Ling Bimantara](https://www.facebook.com/Syehlung)
- [Vanz](https://www.facebook.com/0x0010)

## Group support & bugs report
Facebook : https://www.facebook.com/groups/1631160323785934/

## Kontak dan saran
Kontak, saran, pendapat dll bisa menghubungi saya di facebook : https://www.facebook.com/nurdiantocyk

## Disclaimer
Saya selaku penanggungjawab script menyatakan :
- Tidak ada file, command, virus atau program jahat yang membahayakan di dalam script
- Perangkat editing video berupa ffmpeg, LEGAL dan GRATIS
- Script download video/mp3 dan youtube uploader hanyalah command line bash dan bukan merupakan alat/perangkat utama
