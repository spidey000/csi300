# Global Index Dashboard

A static web application for comparing global stock market indices. Built with vanilla HTML, CSS, and JavaScript - deployable to Netlify or any static hosting.

## Features

- **Multiple Indexes**: S&P 500, IBEX 35, FTSE 100, DAX, Nikkei 225, Dow Jones, NASDAQ, Euro Stoxx 50
- **Currency Conversion**: Switch between USD and EUR
- **Compare Tab**: Select and compare multiple indexes side-by-side with charts
- **Export**: Download data as CSV
- **Auto Date**: Uses yesterday's date for data (accounts for market closures)

## Usage

Simply open `index.html` in a browser or deploy to any static hosting service (Netlify, Vercel, GitHub Pages, etc.).

## Deployment to Netlify

1. Fork or push to GitHub
2. Connect repository to Netlify
3. Deploy - no build configuration needed

## Tech Stack

- Vanilla HTML5/CSS3/JavaScript
- Chart.js for visualizations
- Yahoo Finance API (via CORS proxy) for live data