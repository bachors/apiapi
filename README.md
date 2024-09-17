# apiapi
4u




# Kode-Pos-API
List Propinsi
https://kodepos-2d475.firebaseio.com/list_propinsi.json?print=pretty
<pre>
{
  "p1" : "Bali",
  "p10" : "Jawa Tengah",
  "p11" : "Jawa Timur",
  ...
}
</pre>

List Kota/Kabupaten
https://kodepos-2d475.firebaseio.com/list_kotakab/p9.json?print=pretty
<pre>
{
  "k60" : "Tasikmalaya",
  "k61" : "Pangandaran",
  "k62" : "Ciamis",
  ...
}
</pre>

List Kecamatan, Kelurahan & Kodepos
https://kodepos-2d475.firebaseio.com/kota_kab/k69.json?print=pretty
<pre>
[
	{
	  "kecamatan" : "Cibiuk",
	  "kelurahan" : "Majasari",
	  "kodepos" : "44193"
	}, {
	  "kecamatan" : "Cibiuk",
	  "kelurahan" : "Cibiuk Kidul",
	  "kodepos" : "44193"
	}, {
	  "kecamatan" : "Cibiuk",
	  "kelurahan" : "Cipareuan",
	  "kodepos" : "44193"
	},
	...
]
</pre>



# NIK KTP
https://github.com/bachors/nik_parse.js

https://script.google.com/macros/s/AKfycbwwGKJ6JU7xyfpl_fwQpjsOjzoHZAUzTyOsnXJnbNuDyTx8aqvx5OX8TXHGKUT-OTh5/exec?nik=3204110712970001
<pre>
{
  "status": "success",
  "nik": "3204110712970001",
  "provinsi": "JAWA BARAT",
  "kotakab": "KAB. BANDUNG",
  "kecamatan": "KATAPANG",
  "kodepos": "40921",
  "kelamin": "LAKI-LAKI",
  "lahir": "07/12/1997",
  "pasaran": "Minggu Wage, 7 Desember 1997",
  "usia": "26 Tahun 9 Bulan 4 Hari",
  "ultah": "2 Bulan 27 Hari Lagi",
  "zodiak": "Sagitarius",
  "uniqcode": "0001"
}
</pre>



# Al Quran
Sekarang tersedia data versi offlinenya ditambah perbaikan di bagian link audio, dimana di versi onlinenya link audio belum diperbaiki.
Data Offline https://github.com/bachors/Al-Quran-ID-API/blob/master/offline/data.json

List Surat Online

Firebase: https://al-quran-8d642.firebaseio.com/data.json?print=pretty

Npoint: https://api.npoint.io/99c279bb173a6e28359c/data
<pre>
[
	{
	  "arti" : "Pembukaan",
	  "asma" : "الفاتحة",
	  "audio" : "http://ia802609.us.archive.org/13/items/quraninindonesia/001AlFaatihah.mp3",
	  "ayat" : 7,
	  "keterangan" : "...",
	  "nama" : "Al Fatihah",
	  "nomor" : "1",
	  "rukuk" : "1",
	  "type" : "mekah",
	  "urut" : "5"
	},
	...
]
</pre>


List Ayat Online

Firebase: https://al-quran-8d642.firebaseio.com/surat/1.json?print=pretty

Npoint: https://api.npoint.io/99c279bb173a6e28359c/surat/1
<pre>
[
	{
	  "ar" : "بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ",
	  "id" : "Dengan menyebut nama Allah Yang Maha Pemurah lagi Maha Penyayang.",
	  "nomor" : "1",
	  "tr" : "..."
	},
	...
]
</pre>



# Kamus Besar Bahasa Indonesia
https://github.com/bachors/KBBI.sql



# Zodiak Harian
https://script.google.com/macros/s/AKfycbywRYYUjvLXuKA0Ad2CUJta3lRDA6RTtHMzWMmFY9jaPzqa9WdWgO9iROHQxi_L9qqK/exec
<pre>
{
    "status": "success",
    "date": "11-9-2024",
    "aries": "...",
    "taurus": "...",
    "gemini": "...",
    "cancer": "...",
    "leo": "...",
    "virgo": "...",
    "libra": "...",
    "scorpio": "...",
    "sagitarius": "...",
    "capricorn": "...",
    "aquarius": "...",
    "pisces": "..."
}
</pre>



# Hari Libur & Cuti Nasional
https://script.google.com/macros/s/AKfycbxTj7WY21RLM8RO6biCeobN5BGAzRUgvfzGxvGJ-Scww6rsgXZWIbK0WSpMjhac5vxs/exec?tahun=2025
<pre>
{
  "status": "success",
  "2025": {
    "2025-01-01": "Hari Tahun Baru",
    "2025-01-28": "Isra Mikraj Nabi Muhammad (belum pasti)",
    ...
  },
  "data": [
    {
      "tanggal": "01",
      "bulan": "Jan",
      "title": "Hari Tahun Baru"
    },
    {
      "tanggal": "28",
      "bulan": "Jan",
      "title": "Isra Mikraj Nabi Muhammad (belum pasti)"
    },
    ...
  ]
}
</pre>



# HLR Lookup
https://script.google.com/macros/s/AKfycbwx_d7KPLH1x2AjCf8yfAAvOCueZZxteegaormYL3i9xf2ejkMwodJVHPB0OZeEZ_Pc_A/exec?no=0852353664
<pre>
{
  "status": "success",
  "aw": "0852353664",
  "number": "0852353664",
  "number_code": "62",
  "type": "mobile",
  "country": "Indonesia",
  "country_code": "ID",
  "city": "Surabaya, Malang, Madiun, Jember",
  "provider": "Telkomsel Kartu AS",
  "timezone": "Asia/Jakarta"
}
</pre>



# Lirik Lagu
Judul
https://script.google.com/macros/s/AKfycbwFOEAjPXUY8XwDE6rPBFJVFq56_FNcXD5SnM7ZXfddN8Sbqb84lhreMsQ-nY4QNxzOIQ/exec?judul=rungkad
<pre>
{
    "status": "success",
    "data": [{
            "judul": "Rungkad (Japanese Ver. Cover) by Forysca & Saskia",
            "lirik": "F5DG64TZONRWCLLBNZSC243BONVWSYJNOJ2W4Z3LMFSC22TBOBQW4ZLTMUWXMZLSFVRW65TFOIWWY6LSNFRXG"
        }, {
            "judul": "Rungkad by Vicky Prasetyo",
            "lirik": "F5LGSY3LPEWXA4TBONSXI6LPFVZHK3THNNQWILLMPFZGSY3T"
        }, {
            "judul": "Sway by Bic Runga",
            "lirik": "F5BGSYZNOJ2W4Z3BFVZXOYLZFVWHS4TJMNZQ"
        }
    ]
}
</pre>
Lirik
https://script.google.com/macros/s/AKfycbwFOEAjPXUY8XwDE6rPBFJVFq56_FNcXD5SnM7ZXfddN8Sbqb84lhreMsQ-nY4QNxzOIQ/exec?lirik=F5LGSY3LPEWXA4TBONSXI6LPFVZHK3THNNQWILLMPFZGSY3T
<pre>
{
    "status": "success",
    "data": "[Lirik &quot;Rungkad&quot;]\n\n[Intro]\nRungkad entek entekan\nKelangan kowe sing paling tak sayang\nBondoku melayang tego tenan\nTangis tangisan\nRungkad entek entekan\nTresno tulusku mung dinggo dolanan\nStop mencintaimu\nGawe aku ngelu\n\n[Verse]\nMungkin\nAku terlalu cinta\nAku terlalu sayang nganti ra kroso dilarani\nPancen\nKu akui ku salah\nTerlalu percaya mergo mung nyawang rupo\n\n[Pre-Chorus]\nSaiki aku wes sadar\nTerlalu goblok mencintaimu\n\n[Chorus]\nRungkad entek entekan\nKelangan kowe sing paling tak sayang\nBondoku melayang tego tenan\nTangis tangisan\nRungkad entek entekan\nTresno tulusku mung dinggo dolanan\nStop mencintaimu\nGawe aku ngelu"
}
</pre>


# UNDANG-UNDANG & PANCASILA
PANCASILA https://api.npoint.io/68bdeeeaf95739432e74

UUD 1945 https://api.npoint.io/bb286bbb0d5d782f8466

KUHP https://api.npoint.io/c30ddb1bfd31aa78adc1

KUHPERDATA https://api.npoint.io/e0e154ddb62f296577f6

KUHD https://api.npoint.io/039466ea448182467b5c

KUHAP https://api.npoint.io/9974d514b2503c99a089


# Yang lain nanti nyusul disini
