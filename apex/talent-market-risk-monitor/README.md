# Talent Market Risk Monitor
Oracle APEX REST Dashboard Pattern

Standalone Oracle APEX project demonstrating a REST-driven dashboard using the World Bank API. 
This project is independent from the earlier TLX APEX Notes releases (rel-1 / rel-1.1) contained in this repository.

This project demonstrates a REST integration pattern using Oracle APEX native REST Data Sources.

A public World Bank API is consumed dynamically to populate a JET chart and an interactive report.
Users can select country and indicator parameters, triggering asynchronous region refresh.

## Components Used

- REST Data Sources
- URL pattern parameters
- Dynamic Actions
- Interactive Report
- JET Chart

## Application Preview

doc/screenshots/dashboard_running.png
doc/screenshots/rest_datasource_test_parsed_data.png

## SQL Export

The full Oracle APEX application export is available in:

/sql/talent_market_risk_monitor_v1.0.sql

## Blog Article

Full technical explanation available on:

https://www.tlxlab.ch