## Projeyi Ayağa Kaldırma Adımları

- repoyu klonlayın
- projede terminali açın ve `cd app` ile app klasörüne gelin
- node_modules için `yarn install` veya `node install` çalıştırın
- `node install` için hata alırsanız, `node update` çalıştırın
- projede terminali açın ve `cd server` ile server klasörüne gelin
- node_modules için `npm install` çalıştırın
- serveri ayağa kaldırmak için `npm start`, çalışmaz ise `node index`.
- projede terminali açın ve `cd app` ile app klasörüne gelin
- uygulamayı ayağa kaldırmak için,  `npx expo start`.

Not: Server ile mobil app'in bağlantısı local bir bağlantıdır. Bu nedenle backend'in çalıştığı bilgisayırın ip adresini,
app klasörü altındaki `config.js` dosyasının içindeki `SOCKET_URL` kısmına yazmalısınız.
- cmd'yi açın ip config yazın
- IPV4 adresini kopyalayın
- `config.js` içinde `SOCKET_URL` 'ye  yapıştırın.
