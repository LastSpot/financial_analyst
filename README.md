# Financial Analyst

A volatility-based portfolio allocation framework using the **CBOE Volatility Index (VIX)** as the primary regime indicator.

## Overview

This repository provides systematic allocation guidelines that adjust portfolio weights across equity, sector, and hedge exposures depending on market volatility. The strategy is documented in the [Portfolio Guide](portfolio/README.md).

## Portfolio Guide

The [portfolio guide](portfolio/) defines four volatility regimes and recommended allocations for each:

| Regime              | VIX Range | Guide                    |
|---------------------|-----------|--------------------------|
| Low volatility      | &lt; 15   | [low_volatility.md](portfolio/low_volatility.md)   |
| Normal volatility   | 15–25     | [normal_volatility.md](portfolio/normal_volatility.md) |
| High volatility     | 25–35     | [high_volatity.md](portfolio/high_volatity.md)   |
| Panic volatility    | &gt; 35   | [panic_volatility.md](portfolio/panic_volatility.md)   |
