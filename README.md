# retail-market-analysis
A business intelligence case study simulating how a digital music retailer or subscription platform (in the style of iTunes) could use its own sales and customer data to answer core commercial questions: which markets drive the most revenue, who the highest-value customers are, and which artists perform best.

Overview

Raw transactional data — customers, invoices, tracks, and artists — was modeled and queried using SQL to build a clean relational structure, then visualized in Power BI to surface patterns a sales, marketing, or retention team could actually act on.

Problem / Motivation

A retailer sitting on raw transaction logs can't answer "where should we focus?" without first turning that data into something readable. This project answers three specific business questions:


Which countries/markets generate the most revenue, and how concentrated is that revenue?
Who are the highest-value customers, and how much of total spend do they represent?
Which artists and albums drive the most engagement, and does that match where the revenue comes from?


Data


Source: Raw CSV files covering customers, invoices/line items, tracks, and artists on iTunes
Processing: Converted from CSV into a structured relational database using SQL (iTunesDB Analysis.sql) — joins across customers, invoices, and track/artist tables to build the metrics below
Visualization: Power BI, using the modeled SQL output as its data source
