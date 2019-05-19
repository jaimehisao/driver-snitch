# driver-snitch

## Introduction
Do you ever wonder if you are driving around responsible people? Do you sometimes wonder if this people have outstanding tickets in their cars?
Driving Snitch does just that, it reads licence plates and checks a publicly available database to see if the car has any outstanding tickets in a given municipality.

## How does it work?
The software scans the cars plates using a camera and then the software uses Web Scraping to fetch the cars ticket data, this data is then processed and shown to the end user as a video overlay or a text-based output. 

## Current Project Challenges
- Be able to accurately detect the plates of cars in front (Only query 80% confidence and above).
- Quickly detect the plates and query them against the database. 
- Not spam the datbase by querying the same plate over and over again (Think one scan per 24 hour cap per plate).

## Why?
For no good reason, just as a way to learn about OCR, OpenCV, Python and Web Scraping in a fun and interesting way.

## Current Software Restrictions
- The database where tickets are queried against only works in Nuevo León, Mexico.

## Warnings and Disclaimers
I'm not responsible for any misuse of this software in any way, shape or form. While driving always keep your eyes on the road and not in your device(s).

