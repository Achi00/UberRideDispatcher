# UberRideDispatcher

### Plan

OpenStreetMap
OSRM
Leaflet or MapLibre

Simulate fake drives who follows real roads

Uber's H3 grid system

system will offer nearest driver with 15 second timeout, if declined of not answered it offeres another driver, two matcher instances never assign to same driver

trip states: requested, accepted/declined, arrived, in progress, completed

distributed service may be added on payment, receipt, rating and analytics. if any service is down message should be kept for foture retry with idempotency
count demand and supply per cell over one-minute windows from the event stream, and raise prices where riders outnumber drivers.