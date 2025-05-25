# Historia y Funcionamiento de Bitcoin v0.1

<p align="center">
  <img src="https://bitcoin.org/img/icons/opengraph.png?1648897668" alt="Logo Bitcoin" width="200"/>
</p>

## 1. Contexto Histórico y Lanzamiento

### 🗓 Fechas Clave

- **31 de octubre de 2008:** Satoshi Nakamoto publica el whitepaper titulado _"Bitcoin: A Peer-to-Peer Electronic Cash System"_ a través de la lista de correo de criptografía de metzdowd.com.
- **3 de enero de 2009:** Se mina el bloque génesis (bloque 0) de la red Bitcoin, marcando oficialmente el nacimiento del sistema.
- **9 de enero de 2009:** Satoshi lanza el software Bitcoin v0.1 (disponible en SourceForge), dando inicio formal a la red P2P de Bitcoin.

<p align="center">
  <img src="[https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Genesis_block.png/800px-Genesis_block.png]" alt="Bloque Génesis de Bitcoin" width="600"/>
  <br/>
  <i>Bloque Génesis de Bitcoin</i>
</p>

### ⚙️ Detalles Técnicos de Bitcoin v0.1

- **Lenguaje:** C++
- **Sistema operativo:** Windows (las primeras versiones eran muy limitadas para Linux)
- **Protocolo P2P:** Propio, sin usar otras redes existentes.
- **Algoritmo de consenso:** Proof-of-Work (PoW) usando SHA-256 como función de hash.
- **Estructura de bloque:** Versión, hash del bloque anterior, Merkle Root, timestamp, bits (dificultad), nonce.
- **Tiempo promedio entre bloques:** ~10 minutos.
- **Recompensa por bloque:** 50 BTC (sin comisiones relevantes en esa etapa).
- **Suministro total:** Limitado a 21 millones de bitcoins, con reducción progresiva (halving cada 210,000 bloques).

### 👨‍💻 Primeros Adoptantes y Mineros

- **Satoshi Nakamoto:** Minó los primeros bloques en solitario.
- **Hal Finney:** Primer receptor de una transacción Bitcoin (10 BTC). Ayudó a probar el sistema casi desde el inicio.
- **Otros nombres notables:** Martti Malmi (sirius), Laszlo Hanyecz, Gavin Andresen (posterior desarrollador clave).

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Bitcoin_Blockchain_Structure.png" alt="Estructura Blockchain Bitcoin" width="600"/>
  <br/>
  <i>Estructura de la Blockchain de Bitcoin</i>
</p>

---

## 2. Funcionamiento de la Blockchain en Bitcoin v0.1

### 🧱 Estructura Técnica de la Blockchain

- Cadena de bloques enlazados por hash.
- Cada bloque contenía un conjunto de transacciones, agrupadas en un árbol de Merkle.
- Los nodos verificaban que los hashes y firmas criptográficas coincidieran antes de aceptar un bloque.

### ⚒️ Minado Inicial

- **Hardware:** CPUs convencionales (p. ej., Intel Core 2 Duo o AMD Athlon).
- **Hash rate estimado:** ~7 MH/s en toda la red en los primeros días.
- **Dificultad inicial:** 1 (la más baja posible). Tardó varios días en ajustarse (2016 bloques ≈ 2 semanas).

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*9rl6k4mlT8x6Q0nQdn8qQw.png" alt="CPU Mining" width="500"/>
  <br/>
  <i>Minado de Bitcoin con CPU en los primeros días</i>
</p>

### 💸 Primeras Transacciones

- **12 de enero de 2009:** Hal Finney recibe 10 BTC de Satoshi Nakamoto en la primera transacción persona a persona registrada (bloque #170).
- Durante los primeros meses, muchas transacciones se realizaron entre Satoshi y los pocos colaboradores, como pruebas de funcionamiento.

---

## 3. Estadísticas Económicas y Financieras

### 💰 Valor Monetario Inicial

- En 2009, Bitcoin no tenía valor en dinero fiat.
- **Octubre de 2009:** Primer tipo de cambio informal: 1 BTC ≈ 0.00076 USD (basado en el costo de electricidad para minar un BTC).
- **Mayo de 2010:** La famosa compra de dos pizzas por 10,000 BTC por Laszlo Hanyecz establece la primera transacción comercial.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Bitcoin_pizza.jpg" alt="Bitcoin Pizza" width="400"/>
  <br/>
  <i>Laszlo Hanyecz y la famosa compra de pizzas con Bitcoin</i>
</p>

### 📊 Datos de Adopción

- **Nodos activos:** Se estima solo una docena de nodos activos simultáneamente en los primeros meses.
- **Transacciones diarias:** Menos de 10 por día los primeros meses; crecimiento lento en 2009 y 2010.
- **Tamaño de la blockchain:**
  - Marzo 2009: <1 MB.
  - Finales de 2009: ≈2 MB.
  - Actualmente: >550 GB (2025).

### 🧨 Eventos Clave

- **2010:** Vulnerabilidad de overflow (bloque 74638) permitió la creación de 184 mil millones de BTC. Fue solucionada rápidamente con un hard fork.
- **2011 en adelante:** Aparece Silk Road y se expande el uso de Bitcoin en mercados oscuros.

---

## 4. Impacto Social, Económico y Cultural

### 🌐 Impacto Social

- Comunidad formada en foros como Bitcointalk (fundado por Satoshi en noviembre de 2009).
- Interés principalmente de criptógrafos, desarrolladores y miembros de la cultura cypherpunk.
- Poco interés institucional; la mayoría de economistas lo ignoraban o lo veían como una curiosidad técnica.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Bitcoin_talk_forum.png" alt="Foro Bitcointalk" width="600"/>
  <br/>
  <i>Foro Bitcointalk, epicentro de la comunidad inicial</i>
</p>

### 💹 Impacto Económico

- **Desafíos iniciales:** Baja liquidez, cero regulación, percepción de riesgo alto.
- **Uso en mercados oscuros:** A partir de 2011, Bitcoin gana notoriedad como medio de pago en mercados como Silk Road, marcando un punto de inflexión en su reputación pública.

### 🎭 Impacto Cultural

- Influencia directa del movimiento cypherpunk, que defendía el uso de herramientas criptográficas para proteger la privacidad individual.
- Inspiración en propuestas previas como b-money (Wei Dai), Hashcash (Adam Back) y Bit Gold (Nick Szabo).
- Estimuló la creación de otras criptomonedas: Litecoin (2011), Namecoin, etc.
- Dio origen a una cultura que mezcla anarquismo digital, economía descentralizada y libertarismo.

---

## 5. Evolución y Legado

### 🐛 Problemas de Bitcoin v0.1

- Código sin modularidad, difícil de escalar.
- Seguridad limitada ante ataques Sybil.
- Sin soporte nativo para wallets móviles ni escalabilidad (cada nodo debía descargar toda la blockchain).
- Vulnerabilidad del overflow en 2010.

### 🔄 Comparación con Versiones Posteriores

| Versión        | Cambios clave                                                                  |
|----------------|-------------------------------------------------------------------------------|
| Bitcoin v0.3   | Introducción de soporte para Linux, mejoras en la UI.                         |
| v0.7-v0.8      | Mejora en el manejo de bloques grandes, mayor estabilidad.                    |
| SegWit (2017)  | Separación de firmas de transacciones → más eficiencia y menor tamaño.        |
| Taproot (2021) | Mejoras de privacidad y habilitación de contratos inteligentes más eficientes.|

---

## 📌 Conclusión

Bitcoin v0.1 fue un hito revolucionario que combinó conceptos criptográficos, P2P y económicos en una implementación funcional. Aunque rudimentaria, esta versión sentó las bases del actual ecosistema de criptomonedas. Su impacto ha sido transformador no solo en la economía digital, sino en la forma en que concebimos el dinero, la privacidad y la descentralización.

---

## 📚 Referencias Bibliográficas

- Satoshi Nakamoto. (2008). [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
- [Historia de Bitcoin en la Wikipedia](https://es.wikipedia.org/wiki/Bitcoin)
- [Bitcoin Whitepaper traducido al español](https://www.bitcoin.org/es/bitcoin-paper)
- [Genesis Block - Bitcoin Wiki](https://en.bitcoin.it/wiki/Genesis_block)
- [Bitcointalk Forum](https://bitcointalk.org/)
- [Laszlo Hanyecz y la pizza Bitcoin](https://bitcoinpizzaindex.net/)
- [Revisión del bug del overflow de 2010](https://bitcointalk.org/index.php?topic=822.0)
- [Hashcash - Adam Back](https://en.wikipedia.org/wiki/Hashcash)
- [Bit Gold - Nick Szabo](https://nakamotoinstitute.org/bit-gold/)
- [Wei Dai - b-money](https://nakamotoinstitute.org/b-money/)
