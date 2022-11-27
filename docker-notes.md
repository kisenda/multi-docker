#install React
npm install --location=global create-react-app

create-react-app 'namaProject'

buat file : Dockerfile.dev
isinya? as it is. contek aj. pahami setelahny

pastikan ter-install docker
jalankan 'docker build -f Dockerfile.dev .'
lalu hapus node_modules
jalankan docker build -f Dockerfile.dev . (utk ke 2x-nya)

lalu utk eksekusi : docker run -p 3000:3000 'UUID yg terbentuk dari proses diatas' (-p mapping port / menyamakan alamat dan tempat tujuan )

docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app UUID (ada revisi : lihat di materi 70 )
