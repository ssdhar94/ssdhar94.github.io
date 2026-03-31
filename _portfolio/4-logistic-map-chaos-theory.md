---
title: "Logistic Map — Chaos Theory Applications"
excerpt: "Explored the logistic equation and its applications in pseudo-random number generation, image encryption, fractal geometry, and COVID-19 pandemic modeling using Python and MATLAB."
collection: portfolio
---

## Overview

A group project for the course **ME5010 (Mathematics for Engineers)** exploring the behaviour of the **logistic map** — a simple nonlinear equation that exhibits chaotic dynamics. The project demonstrates how a deterministic system can produce unpredictable, seemingly random outputs, and leverages this property across several practical applications.

**Logistic Equation:** `x_{n+1} = r * x_n * (1 - x_n)`

## Topics Covered

- **Logistic Equation Analysis** — fixed points, period doubling, bifurcation maps, cobweb maps
- **Pseudo-Random Number Generator (PRNG)** — exploiting the chaotic nature of the logistic map at `r=4` to generate uniformly distributed random numbers
- **Image Encryption** — using the PRNG to encrypt image data
- **Fractal Geometry** — generating Sierpiński Triangle and Barnsley's Fern
- **Forecasting Model** — applying the logistic function to model product diffusion and market acceptance
- **COVID-19 Pandemic Modelling** — applying the generalized Verhulst (logistic) equation to India's COVID-19 infection data

## Group Members

Aman Gautam, Neeli Shyam Sridhar, Boddepalli Pavan Kumar, Rudramuni TS, Nitesh Singh

## Tech Stack

- **Python** — NumPy, Matplotlib, Numba (interactive bifurcation map, PRNG, fractals, encryption)
- **MATLAB** — cobweb animation, logistic business model, generalized Verhulst equation

## Links

- [Source Code (GitHub)](https://github.com/shyamsridhar/ME5010Project)
