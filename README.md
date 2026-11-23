# Mohamed-Walid Chaabane

**Engineering student at IMT Atlantique · Quantitative finance & machine learning**

I am a second-year engineering student at IMT Atlantique (graduating in 2028), with a background in mathematics and physics. I build tools to price derivatives, check models against each other and apply machine learning to market data.

**Currently looking for an internship in derivatives valuation, quantitative analysis or market risk, from 29 March to 31 August 2027 (Paris).**

---

### Featured projects

**[equity-derivatives-lab](https://github.com/ch-moh/equity-derivatives-lab)**: equity option pricing and model validation in Python
- Black-Scholes with analytic Greeks and implied volatility, Cox-Ross-Rubinstein tree (European and American exercise), Monte Carlo with antithetic variates
- Dupire local volatility from an implied volatility surface, with detection and reporting of arbitrageable regions
- Nearest correlation matrix (Higham) and basket option pricing
- Each method is cross-checked against the others and covered by unit tests (pytest)

**[optiver-rv](https://github.com/ch-moh/optiver-rv)**: realized volatility forecasting from order book data ([Kaggle notebook](https://www.kaggle.com/code/chwalid/optiver-realized-volatility-lightgbm))
- 167 million order book updates across ~112 stocks
- Microstructure features (spread, order imbalance, depth) and a LightGBM model trained to optimise RMSPE directly
- Time-grouped cross-validation to avoid leakage; RMSPE of 0.239 vs 0.341 for the baseline (−30%)

**3D MRI segmentation with a Transformer (Swin UNETR)**: IMT Atlantique course project, PyTorch / MONAI
- Segmentation of 4 organs on 3D MRI scans with heavily imbalanced data; mean Dice score above 0.92 on held-out scans

---

### Toolbox

- **Quantitative finance**: option pricing (Black-Scholes, trees, Monte Carlo, local volatility), Greeks, implied volatility, market microstructure
- **Mathematics**: probability, stochastic calculus, measure theory, numerical analysis, statistics
- **Programming**: Python (NumPy, SciPy, pandas, scikit-learn, LightGBM, PyTorch), pytest, Git, SQL, Docker, MATLAB

### Contact

[LinkedIn](https://www.linkedin.com/in/mohamed-walid-chaabane/) · [Kaggle](https://www.kaggle.com/chwalid) · mohamed.chaabane@imt-atlantique.net
