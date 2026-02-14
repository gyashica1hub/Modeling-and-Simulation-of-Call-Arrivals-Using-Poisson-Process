# 📞 Call Arrival Analysis using Poisson Process & Simulation

This project models and analyzes a **call arrival system** using **Poisson processes** and **exponential interarrival times**.  
It combines **analytical probability calculations** with **simulation and Monte Carlo methods** to study system behavior and estimate required resources.

---

## 🚀 Features
- Analytical probability calculations using Poisson distribution
- Waiting time analysis using exponential distribution
- Simulation of call arrivals over a 9-hour business day
- Visualization of call timelines and hourly distributions
- Monte Carlo simulation for peak-load analysis
- System load estimation and staffing recommendation

---

## 🧮 Model Assumptions
- Call arrivals follow a **Poisson process**
- Interarrival times are **exponentially distributed**
- Average arrival rate is constant
- Calls are independent of each other

---

## ⚙️ Parameters
| Parameter | Value |
|--------|------|
| Average call rate (λ) | 20 calls/hour |
| Business hours | 9 hours |
| Total time | 540 minutes |
| Monte Carlo simulations | 1000 |

---

## 📊 Project Structure

### Part A: Analytical Analysis
- Probability of exactly *k* calls in a given time interval
- Probability of exceeding a call threshold
- Expected waiting time between calls
- Queue load estimation over short intervals

### Part B: Simulation
- Simulation of interarrival times
- Call arrival timeline visualization
- Histogram of calls per hour
- Monte Carlo simulation of hourly call volume
- Comparison of simulated vs theoretical probabilities
- Estimation of system capacity using percentiles

---

## 📈 Visual Outputs
- Call arrival timeline over a 9-hour day
- Hourly call distribution histogram
- Monte Carlo frequency distribution of call counts

---

## 🛠️ Technologies Used
- Python 3
- NumPy
- SciPy
- Matplotlib
- Seaborn

---

## ▶️ How to Run

### 1️⃣ Install Dependencies
```bash
pip install numpy scipy matplotlib seaborn
