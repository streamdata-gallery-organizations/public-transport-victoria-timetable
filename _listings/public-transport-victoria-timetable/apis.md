---
name: Public Transport Victoria Timetable
x-slug: public-transport-victoria-timetable
description: The PTV Timetable API provides direct access to Public Transport Victoria&rsquo;s
  public transport timetable data. The API returns scheduled timetable, route and
  stop data for all metropolitan and regional train, tram and bus services in Victoria,
  including Night Network(Night Train and Night Tram data are included in metropolitan
  train and tram services data, respectively, whereas Night Bus is a separate route
  type). The API also returns real-time data for metropolitan train, tram and bus
  services (where this data is made available to PTV), as well as disruption information,
  stop facility information, and access to myki ticket outlet data.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Public Transport Victoria Timetable
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/apis.md
specificationVersion: "0.14"
apis:
- name: PTV Timetable API - Version 3 Get V3 Departures Route Type Route Type Stop
    Stop
  x-api-slug: ptv-timetable-api--version-3
  description: View departures for all routes from a stop.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/departures/route_type/{route_type}/stop/{stop_id}
  tags: Departures,Route,Type,Route,Type,Stop,Stop,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3departuresroute-typeroute-typestopstop-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3departuresroute-typeroute-typestopstop-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Departures Route Type Route Type Stop
    Stop Route Route
  x-api-slug: ptv-timetable-api--version-3
  description: View departures for a specific route from a stop.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/departures/route_type/{route_type}/stop/{stop_id}/route/{route_id}
  tags: Departures,Route,Type,Route,Type,Stop,Stop,Id,Route,Route,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3departuresroute-typeroute-typestopstop-idrouteroute-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3departuresroute-typeroute-typestopstop-idrouteroute-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Directions Route Route
  x-api-slug: ptv-timetable-api--version-3
  description: View directions that a route travels in.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/directions/route/{route_id}
  tags: Directions,Route,Route,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsrouteroute-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsrouteroute-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Directions Direction
  x-api-slug: ptv-timetable-api--version-3
  description: View all routes for a direction of travel.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/directions/{direction_id}
  tags: Directions,Direction,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsdirection-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsdirection-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Directions Direction Route Type Route
    Type
  x-api-slug: ptv-timetable-api--version-3
  description: View all routes of a particular type for a direction of travel.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/directions/{direction_id}/route_type/{route_type}
  tags: Directions,Direction,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsdirection-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3directionsdirection-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Disruptions
  x-api-slug: ptv-timetable-api--version-3
  description: View all disruptions for all route types.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/disruptions
  tags: Disruptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptions-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Disruptions Route Route
  x-api-slug: ptv-timetable-api--version-3
  description: View all disruptions for a particular route.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/disruptions/route/{route_id}
  tags: Disruptions,Route,Route,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptionsrouteroute-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptionsrouteroute-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Disruptions Disruption
  x-api-slug: ptv-timetable-api--version-3
  description: View a specific disruption.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/disruptions/{disruption_id}
  tags: Disruptions,Disruption,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptionsdisruption-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3disruptionsdisruption-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Pattern Run Run Route Type Route Type
  x-api-slug: ptv-timetable-api--version-3
  description: View the stopping pattern for a specific trip/service run.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/pattern/run/{run_id}/route_type/{route_type}
  tags: Pattern,Run,Run,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3patternrunrun-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3patternrunrun-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Route Types
  x-api-slug: ptv-timetable-api--version-3
  description: View all route types and their names.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/route_types
  tags: Route,Types
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3route-types-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3route-types-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Routes
  x-api-slug: ptv-timetable-api--version-3
  description: View route names and numbers for all routes.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/routes
  tags: Routes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3routes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3routes-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Routes Route
  x-api-slug: ptv-timetable-api--version-3
  description: View route name and number for specific route id.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/routes/{route_id}
  tags: Routes,Route,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3routesroute-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3routesroute-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Runs Route Route
  x-api-slug: ptv-timetable-api--version-3
  description: View all trip/service runs for a specific route id.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/runs/route/{route_id}
  tags: Runs,Route,Route,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrouteroute-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrouteroute-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Runs Route Route Route Type Route Type
  x-api-slug: ptv-timetable-api--version-3
  description: View all trip/service runs for a specific route id and route type.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/runs/route/{route_id}/route_type/{route_type}
  tags: Runs,Route,Route,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrouteroute-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrouteroute-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Runs Run
  x-api-slug: ptv-timetable-api--version-3
  description: View all trip/service runs for a specific run id.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/runs/{run_id}
  tags: Runs,Run,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrun-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrun-id-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Runs Run Route Type Route Type
  x-api-slug: ptv-timetable-api--version-3
  description: View the trip/service run for a specific run id and route type.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/runs/{run_id}/route_type/{route_type}
  tags: Runs,Run,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrun-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3runsrun-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Search Search Term
  x-api-slug: ptv-timetable-api--version-3
  description: View stops, routes and myki ticket outlets that match the search term.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/search/{search_term}
  tags: Search,Search,Term
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3searchsearch-term-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3searchsearch-term-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Stops Location Latitude , Longitude
  x-api-slug: ptv-timetable-api--version-3
  description: View all stops near a specific location.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/stops/location/{latitude},{longitude}
  tags: Stops,Location,Latitude,Longitude
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopslocationlatitudelongitude-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopslocationlatitudelongitude-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Stops Route Route Route Type Route Type
  x-api-slug: ptv-timetable-api--version-3
  description: View all stops on a specific route.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/stops/route/{route_id}/route_type/{route_type}
  tags: Stops,Route,Route,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopsrouteroute-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopsrouteroute-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3 Get V3 Stops Stop Route Type Route Type
  x-api-slug: ptv-timetable-api--version-3
  description: View facilities at a specific stop (metro and v/line stations only).
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au////v3/stops/{stop_id}/route_type/{route_type}
  tags: Stops,Stop,Id,Route,Type,Route,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopsstop-idroute-typeroute-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/v3stopsstop-idroute-typeroute-type-get-openapi.md
- name: PTV Timetable API - Version 3
  x-api-slug: ptv-timetable-api--version-3
  description: The PTV Timetable API provides direct access to Public Transport Victoria&rsquo;s
    public transport timetable data. The API returns scheduled timetable, route and
    stop data for all metropolitan and regional train, tram and bus services in Victoria,
    including Night Network(Night Train and Night Tram data are included in metropolitan
    train and tram services data, respectively, whereas Night Bus is a separate route
    type). The API also returns real-time data for metropolitan train, tram and bus
    services (where this data is made available to PTV), as well as disruption information,
    stop facility information, and access to myki ticket outlet data.
  image: ""
  humanURL: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
  baseURL: https://timetableapi.ptv.vic.gov.au//
  tags: Public Transport Victoria Timetable
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/public-transport-victoria-timetable/master/_listings/public-transport-victoria-timetable/openapi.md
x-common:
- type: x-website
  url: https://www.ptv.vic.gov.au/about-ptv/data-and-reports/datasets/ptv-timetable-api/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---