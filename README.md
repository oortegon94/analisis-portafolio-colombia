# 📊 Análisis de Portafolio de Inversiones Colombia

Análisis cuantitativo de un portafolio diversificado que combina activos colombianos e internacionales, utilizando técnicas estándar de la industria financiera implementadas en Python.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🎯 Objetivo

Evaluar el comportamiento histórico, las características de riesgo-rendimiento y las oportunidades de optimización de un portafolio que incluye acciones colombianas (Ecopetrol, Bancolombia, ISA, Nutresa), ETFs internacionales (S&P 500), renta fija (bonos US) y commodities (oro).

## 📈 Análisis incluido

| # | Análisis | Descripción |
|---|----------|-------------|
| 1 | **Métricas individuales** | Rendimiento, volatilidad, Sharpe y Maximum Drawdown por activo |
| 2 | **Correlaciones** | Matriz de correlación y evaluación del potencial de diversificación |
| 3 | **Rendimiento del portafolio** | Evolución acumulada vs benchmark (S&P 500) |
| 4 | **Frontera eficiente** | Optimización de Markowitz con simulación Monte Carlo (10,000 portafolios) |
| 5 | **Análisis de riesgo** | Value at Risk (VaR), Expected Shortfall (CVaR) y Maximum Drawdown |
| 6 | **Comparación de estrategias** | Equiponderado vs definido vs máximo Sharpe vs mínima varianza |
| 7 | **Rendimientos móviles** | Consistencia del portafolio en ventanas de 3, 6 y 12 meses |
| 8 | **Contribución al riesgo** | Descomposición del riesgo por activo |

## 🏗️ Composición del portafolio

| Activo | Ticker | Clase | Peso |
|--------|--------|-------|------|
| Ecopetrol | EC | Acción Colombia | 15% |
| Bancolombia | CIB | Acción Colombia | 15% |
| ISA | ISA.CL | Acción Colombia | 10% |
| Nutresa | NGRD | Acción Colombia | 10% |
| S&P 500 | SPY | ETF Internacional | 25% |
| Bonos US | BND | ETF Renta Fija | 10% |
| Oro | GLD | ETF Commodity | 15% |

## 🛠️ Tecnologías

- **Python 3.10+**
- **Pandas** — manipulación y análisis de datos
- **NumPy** — cálculos matriciales y simulación Monte Carlo
- **Matplotlib** — visualización de datos
- **yfinance** — descarga de datos financieros en tiempo real

## 🚀 Cómo ejecutar

### Opción 1: Google Colab (recomendado)

1. Sube el archivo `Analisis_Portafolio_Inversiones_Colombia.ipynb` a [Google Colab](https://colab.research.google.com)
2. Ejecuta todas las celdas (Runtime → Run all)
3. Los datos se descargan automáticamente

### Opción 2: Local

```bash
# Clonar el repositorio
git clone https://github.com/oortegon94/analisis-portafolio-colombia.git
cd analisis-portafolio-colombia

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar el notebook
jupyter notebook Analisis_Portafolio_Inversiones_Colombia.ipynb
```

## 📁 Estructura del repositorio

```
analisis-portafolio-colombia/
├── Analisis_Portafolio_Inversiones_Colombia.ipynb  # Notebook principal
├── README.md
├── requirements.txt
├── LICENSE
└── img/                          # Gráficas generadas
    ├── 01_riesgo_rendimiento.png
    ├── 02_precios_normalizados.png
    ├── 03_correlacion.png
    ├── 04_rendimiento_portafolio.png
    ├── 05_frontera_eficiente.png
    ├── 06_composicion_portafolios.png
    ├── 07_analisis_riesgo.png
    ├── 08_comparacion_estrategias.png
    ├── 09_rendimientos_moviles.png
    └── 10_contribucion_riesgo.png
```

## ⚠️ Disclaimer

Este análisis es un ejercicio educativo y de portafolio profesional. **No constituye asesoría financiera ni recomendación de inversión.** Los rendimientos pasados no garantizan rendimientos futuros. Consulte a un profesional certificado antes de tomar decisiones de inversión.

## 📬 Contacto

**Omar Ortegón**  
Ingeniero Financiero | Analítica de Datos aplicada a Finanzas  
[LinkedIn](https://www.linkedin.com/in/omar-ortegon94)

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver [LICENSE](LICENSE) para más detalles.
