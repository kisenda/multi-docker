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

catatan sementara UUID : df9381ea8a5bc08df75db784f9b41a81f545f07e6eee0493ed9a73cf215f67dc
