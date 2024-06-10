
### Calculadora de Criptomonedas

Esta aplicación es una calculadora de criptomonedas construida con Flask (backend), HTML, JavaScript (frontend), y CSS (diseño). Utiliza la API de CoinMarketCap para proporcionar información actualizada sobre criptomonedas, permitiendo a los usuarios calcular y visualizar sus inversiones.

#### Características
- Obtención de datos en tiempo real desde CoinMarketCap.
- Entrada de usuario para precio de entrada, número de entradas, rango de entrada, y tipo de operación.
- Generación dinámica de tablas de inversión.
- Cálculo del precio promedio de entrada y la inversión total.

#### Tecnologías Utilizadas
- Backend: Flask
- Frontend: HTML, CSS, JavaScript
- API: CoinMarketCap

#### Cómo Ejecutar
1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/juliotoribio/Calculadora_Entradas_Promedio_Trading
   ```
2. **Navegar al directorio del proyecto**:
   ```sh
   cd crypto-calculator
   ```
3. **Instalar dependencias**:
   ```sh
   pip install -r requirements.txt
   ```
4. **Ejecutar la aplicación Flask**:
   ```sh
   flask run
   ```
5. **Acceder a la aplicación**:
   Abre tu navegador web y ve a `http://127.0.0.1:5000/`.

#### Mejoras Futuras
- Integración de base de datos para análisis histórico.
- Autenticación de usuarios para guardar configuraciones.
- Implementación de cálculos financieros avanzados.

---
