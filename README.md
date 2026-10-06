# Integer Overflow Explorer

An interactive browser-based visualization built for SE/CprE 4210: 
Software Analysis and Verification for Safety and Security at Iowa 
State University.

## Live Demo

[View it live on Netlify]((https://4210-overflow-explorer.netlify.app/))

## What it does

This tool helps learners understand integer overflow by letting you 
interact with fixed-width integer values in real time. You can type 
any number, drag a slider, switch between 8, 16, and 32-bit widths, 
and toggle between signed and unsigned to see exactly how the value 
wraps around when it exceeds its boundary.

Features:
- Live binary representation that updates bit by bit as you type
- Capacity meter that fills and turns red as you approach overflow
- Overflow event history log that tracks every wrap-around you trigger
- Signed vs unsigned comparison mode
- References the Ariane 5 rocket failure as a real-world example

## How to run it

Just open index.html in any modern browser. No dependencies, no build 
step, no install needed.

## Built with

HTML, CSS, and vanilla JavaScript. Deployed on Netlify.

## Team

- Mekhi San (sanm20)
- Ash Bhuiyan (mbhuiyan)
- Aaron Dais (dais0006)
- Luke Olsen (ltolsen)

## Course

SE/CprE 4210 — Iowa State University, Fall 2026  
Instructor: Ahmed Tamrawi
