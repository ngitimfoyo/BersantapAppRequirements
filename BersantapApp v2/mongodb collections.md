Bersantap documents

1. Kategori: _id, Nama
2. Spot: _id, Nama, Alamat, Kontak: { telpon: [ //array ], situs: "string", twitter: "str", facebook: "str" }, Deskripsi, Koordinat, Kategori, Komentar: {IdPengguna, Nama, Rating, Komentar}
3. Pengguna: _id, IdPengguna, Nama, Telepon
4. Kontak: { telpon: [ //array ], situs: "string", twitter: "str", facebook: "str" }

sample document:
Kategori = {_id: 234234234234, Nama: "Bengkel"}

Spot = {
_id: 4534534534,
Nama: "Bengkel Eksotis",
Alamat: "Jl Harapan Palsu, Jakarta Utara",
Kontak: "0874 5454 98986;(021)8799 9998",
Deskripsi: "Service ringan;service berat;ganti oli;ganti kabel;permak;cat"
Koordinat: "-2,2342342434;3.23423424",
Kategory : "Bengkel",
Komentar: [{
  IdPengguna: "encep@gmail.com",
  Nama: "Encep",
  Rating: 3,
  Komentar: "Bengkel bagus, murah"
 },
 {
  IdPenggina: "vony@gmail.com",
  Nama: "Vony",
  Rating: 4,
  Komentar: "Tempatnya bersih, recomended deh"
 }]
}

Pengguna = {_id: 2342424234, IdPengguna: "encep@gmail.com", Nama: "Encep", Telepon: "092342423494"}
