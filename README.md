# MATLAB_Kraken_API
MATLAB implementation of the API of www.kraken.com

Links de interés: 
- https://www.kraken.com/features/api
- https://docs.kraken.com/websockets/

M-files
=======

- kraken_api_assetpairs.m: Obtener pares de activos negociables <--- ARREGLAR
URL: https://api.kraken.com/0/public/AssetPairs

- kraken_api_assets.m: Obtener listo de activos
URL: https://api.kraken.com/0/public/Assets

- kraken_api_depth.m: Obtener libro de órdenes para un asset
URL: https://api.kraken.com/0/public/Depth
Ejemplo: https://api.kraken.com/0/public/Depth?pair=xbteur&count=4

- kraken_api_ohlc.m: Obtener datos OHLC (Apertura Máximo Mínimo Cierre)
Ejemplo: https://api.kraken.com/0/public/OHLC?pair=xbtusd	

- kraken_api_spread.m: Obtener datos de spread recientes
Ejemplo: https://api.kraken.com/0/public/Spread?pair=ETHXBT

- kraken_api_ticker.m: Información de Ticker
Ejemplo: https://api.kraken.com/0/public/Ticker?pair=BTCEUR	

- kraken_api_time.m: Obtener la hora del servidor
URL: https://api.kraken.com/0/public/Time

- kraken_api_trades.m: Obtener operaciones recientes
Ejemplo: Ejemplo: https://api.kraken.com/0/public/Spread?pair=ETHXBT

- kraken_public_query.m: monta la URL
- kraken_query.m: Realiza la consulta (pública)
