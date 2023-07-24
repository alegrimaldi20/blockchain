## Blockchain
Este es un DApp NFT Marketplace completo.
Realizado con NodeJS, Hardhat, Solidity, ReactJS, NextJS y Vercel.

## Acciones básicas
Puede crear (mint) nuevos tokens, cargando su imagen y metadatos en IPFS usando Pinata.
Si creó o compró un NFT, también puede venderlo estableciendo un precio y pagando una tarifa de cotización.
Al comprar un NFT, el precio se transferirá al vendedor y la tarifa de cotización al propietario del NFT Marketplace.

### Solo hay dos páginas para ver los NFT del mercado:

- Página de mercado:
Muestra todos los NFT que están disponibles para comprar.
 - Mi página de NFT:
Muestra todas las cuentas NFT creadas, propias y en venta.
Aquí realiza un seguimiento de los NFT que ha creado y comprueba cuánto se han vendido por última vez y su propietario actual.

Si la extensión Metamask no se detecta en la página "Mis NFT", se le solicitará al usuario un mensaje con un botón de descarga.
Si el usuario tiene la extensión, pero no está conectado, se mostrará un mensaje y un botón de conexión.


El frontend se implementa automáticamente mediante la integración de Github de Vercel, pero los contratos deben implementarse manualmente para mantener un mejor control sobre ellos.


![Imagen10000](https://github.com/alegrimaldi20/blockchain/assets/92336281/57893d08-dc94-442a-a0a5-6023e19d9782)

![Imagen3](https://github.com/alegrimaldi20/blockchain/assets/92336281/d3bab880-13ca-44af-9f00-dc13b23ed883)



## Implementacion
- Copie y rellénelo con variables de entorno `.env.local.example.` `.env.local.`
- Ejecutar npm run nodepara iniciar una red de prueba de cadena de bloques EVM local
- Ejecute npm run setup para implementar contratos NFT y Marketplace y realice algunas acciones iniciales en la cadena de bloques local
- Ejecutar npm run dev para iniciar la aplicación frontend
- Asegúrate de usar Localhost 8545como red de Metamaskl
- Ejecutar `npm run deploy:mumbai` para implementar contratos en Polygon`s Testnet (Mumbai).
