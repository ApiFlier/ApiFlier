# Charlie Meeks

Aviation software portfolio focused on self-hosted operational dashboards, live aviation data, route intelligence, and geospatial tools.

## Live Project Links

- [Event Map](https://events.meeks.cc)
- [FlightConn](https://flights.meeks.cc)
- [AirfieldOps Dashboard](https://dashboard.meeks.cc)
- [Aviation Radar](https://radar.meeks.cc)

## Featured Projects

### AirfieldOps
Self-hosted live aviation operations dashboard for airport weather, runway conditions, hazards, alternates, and airport situational awareness.

**Live:** https://dashboard.meeks.cc  
**Repo:** https://github.com/ApiFlier/airfieldops-dashboard  
**Tech:** FastAPI, Docker, SQLite, JavaScript, AviationWeather.gov, NWS, OurAirports

Demonstrates aviation-domain product thinking, public-data integration, Dockerized deployment, automated testing, read-only public mode, and operational dashboard design.

---

### Aviation Radar
Self-hosted aircraft tracking and radar visualization app using live public aviation data sources.

**Live:** https://radar.meeks.cc  
**Repo:** https://github.com/ApiFlier/aviation-radar  
**Tech:** FastAPI/Uvicorn, Redis, Docker, JavaScript, ADS-B data, optional FAA SWIM

Demonstrates live data ingestion, map visualization, container orchestration, optional credential-gated services, and resilient setup behavior.

---

### FlightConn
Airline route intelligence and airline health dashboard for exploring airport routes, carrier service, fare history, schedules, and airline business indicators.

**Live:** https://flights.meeks.cc  
**Repo:** https://github.com/ApiFlier/aviation-route-intelligence  
**Tech:** Flask, MySQL, Docker, JavaScript, BTS aviation datasets

Demonstrates airline data modeling, route-network analysis, historical fare/traffic data, database seeding, and executive-style aviation intelligence views.

---

### Event Map
Self-hosted regional event discovery map for browsing local destinations, farms, markets, and events.

**Live:** https://events.meeks.cc  
**Repo:** https://github.com/ApiFlier/event-map  
**Tech:** Flask, MySQL, Docker, JavaScript, Leaflet/Esri map tiles

Demonstrates geospatial UI, filtering, admin workflows, persistent data, and user-focused product design.
