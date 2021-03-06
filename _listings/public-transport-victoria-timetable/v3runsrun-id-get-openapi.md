---
swagger: "2.0"
x-collection-name: Public Transport Victoria Timetable
x-complete: 0
info:
  title: PTV Timetable API - Version 3 Get V3 Runs Run
  description: View all trip/service runs for a specific run id.
  termsOfService: http://ptv.vic.gov.au/ptv-timetable-api/
  contact:
    name: Public Transport Victoria
    url: http://ptv.vic.gov.au/digital
  version: v3
host: timetableapi.ptv.vic.gov.au
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/departures/route_type/{route_type}/stop/{stop_id}:
    get:
      summary: Get V3 Departures Route Type Route Type Stop Stop
      description: View departures for all routes from a stop.
      operationId: Departures_GetForStop
      x-api-path-slug: v3departuresroute-typeroute-typestopstop-id-get
      parameters:
      - in: query
        name: date_utc
        description: Filter by the date and time of the request (ISO 8601 UTC format)
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: direction_id
        description: Filter by identifier of direction of travel; values returned
          by Directions API - /v3/directions/route/{route_id}
      - in: query
        name: expand
        description: List objects to be returned in full (i
      - in: query
        name: gtfs
        description: Indicates that stop_id parameter will accept GTFS stop_id data
      - in: query
        name: include_cancelled
        description: Indicates if cancelled services (if they exist) are returned
          (default = false) - metropolitan train only
      - in: query
        name: max_results
        description: Maximum number of results returned
      - in: query
        name: platform_numbers
        description: Filter by platform number at stop
      - in: path
        name: route_type
        description: Number identifying transport mode; values returned via RouteTypes
          API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: path
        name: stop_id
        description: Identifier of stop; values returned by Stops API
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Departures
      - Route
      - Type
      - Route
      - Type
      - Stop
      - Stop
      - Id
  /v3/departures/route_type/{route_type}/stop/{stop_id}/route/{route_id}:
    get:
      summary: Get V3 Departures Route Type Route Type Stop Stop Route Route
      description: View departures for a specific route from a stop.
      operationId: Departures_GetForStopAndRoute
      x-api-path-slug: v3departuresroute-typeroute-typestopstop-idrouteroute-id-get
      parameters:
      - in: query
        name: date_utc
        description: Filter by the date and time of the request (ISO 8601 UTC format)
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: direction_id
        description: Filter by identifier of direction of travel; values returned
          by Directions API - /v3/directions/route/{route_id}
      - in: query
        name: expand
        description: List objects to be returned in full (i
      - in: query
        name: gtfs
        description: Indicates that stop_id parameter will accept GTFS stop_id data
      - in: query
        name: include_cancelled
        description: Indicates if cancelled services (if they exist) are returned
          (default = false) - metropolitan train only
      - in: query
        name: max_results
        description: Maximum number of results returned
      - in: path
        name: route_id
        description: Identifier of route; values returned by Routes API - v3/routes
      - in: path
        name: route_type
        description: Number identifying transport mode; values returned via RouteTypes
          API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: path
        name: stop_id
        description: Identifier of stop; values returned by Stops API
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Departures
      - Route
      - Type
      - Route
      - Type
      - Stop
      - Stop
      - Id
      - Route
      - Route
      - Id
  /v3/directions/route/{route_id}:
    get:
      summary: Get V3 Directions Route Route
      description: View directions that a route travels in.
      operationId: Directions_ForRoute
      x-api-path-slug: v3directionsrouteroute-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: route_id
        description: Identifier of route; values returned by Routes API - v3/routes
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Directions
      - Route
      - Route
      - Id
  /v3/directions/{direction_id}:
    get:
      summary: Get V3 Directions Direction
      description: View all routes for a direction of travel.
      operationId: Directions_ForDirection
      x-api-path-slug: v3directionsdirection-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: direction_id
        description: Identifier of direction of travel; values returned by Directions
          API - /v3/directions/route/{route_id}
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Directions
      - Direction
      - Id
  /v3/directions/{direction_id}/route_type/{route_type}:
    get:
      summary: Get V3 Directions Direction Route Type Route Type
      description: View all routes of a particular type for a direction of travel.
      operationId: Directions_ForDirectionAndType
      x-api-path-slug: v3directionsdirection-idroute-typeroute-type-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: direction_id
        description: Identifier of direction of travel; values returned by Directions
          API - /v3/directions/route/{route_id}
      - in: path
        name: route_type
        description: Number identifying transport mode; values returned via RouteTypes
          API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Directions
      - Direction
      - Id
      - Route
      - Type
      - Route
      - Type
  /v3/disruptions:
    get:
      summary: Get V3 Disruptions
      description: View all disruptions for all route types.
      operationId: Disruptions_GetAllDisruptions
      x-api-path-slug: v3disruptions-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: disruption_status
        description: Filter by status of disruption
      - in: query
        name: route_types
        description: Filter by route_type; values returned via RouteTypes API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Disruptions
  /v3/disruptions/route/{route_id}:
    get:
      summary: Get V3 Disruptions Route Route
      description: View all disruptions for a particular route.
      operationId: Disruptions_GetDisruptionsByRoute
      x-api-path-slug: v3disruptionsrouteroute-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: disruption_status
        description: Filter by status of disruption
      - in: path
        name: route_id
        description: Identifier of route; values returned by Routes API - v3/routes
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Disruptions
      - Route
      - Route
      - Id
  /v3/disruptions/{disruption_id}:
    get:
      summary: Get V3 Disruptions Disruption
      description: View a specific disruption.
      operationId: Disruptions_GetDisruptionById
      x-api-path-slug: v3disruptionsdisruption-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: disruption_id
        description: Identifier of disruption; values returned by Disruptions API
          - /v3/disruptions OR /v3/disruptions/route/{route_id}
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Disruptions
      - Disruption
      - Id
  /v3/pattern/run/{run_id}/route_type/{route_type}:
    get:
      summary: Get V3 Pattern Run Run Route Type Route Type
      description: View the stopping pattern for a specific trip/service run.
      operationId: Patterns_GetPatternByRun
      x-api-path-slug: v3patternrunrun-idroute-typeroute-type-get
      parameters:
      - in: query
        name: date_utc
        description: Filter by the date and time of the request (ISO 8601 UTC format)
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: route_type
        description: Number identifying transport mode; values returned via RouteTypes
          API
      - in: path
        name: run_id
        description: Identifier of a trip/service run; values returned by Runs API
          - /v3/route/{route_id} and Departures API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: stop_id
        description: Filter by stop_id; values returned by Stops API
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Pattern
      - Run
      - Run
      - Id
      - Route
      - Type
      - Route
      - Type
  /v3/route_types:
    get:
      summary: Get V3 Route Types
      description: View all route types and their names.
      operationId: RouteTypes_GetRouteTypes
      x-api-path-slug: v3route-types-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Route
      - Types
  /v3/routes:
    get:
      summary: Get V3 Routes
      description: View route names and numbers for all routes.
      operationId: Routes_OneOrMoreRoutes
      x-api-path-slug: v3routes-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: query
        name: route_name
        description: Filter by name  of route (accepts partial route name matches)
      - in: query
        name: route_types
        description: Filter by route_type; values returned via RouteTypes API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Routes
  /v3/routes/{route_id}:
    get:
      summary: Get V3 Routes Route
      description: View route name and number for specific route id.
      operationId: Routes_RouteFromId
      x-api-path-slug: v3routesroute-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: route_id
        description: Identifier of route; values returned by Departures, Directions
          and Disruptions APIs
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Routes
      - Route
      - Id
  /v3/runs/route/{route_id}:
    get:
      summary: Get V3 Runs Route Route
      description: View all trip/service runs for a specific route id.
      operationId: Runs_ForRoute
      x-api-path-slug: v3runsrouteroute-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: route_id
        description: Identifier of route; values returned by Routes API - v3/routes
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Runs
      - Route
      - Route
      - Id
  /v3/runs/route/{route_id}/route_type/{route_type}:
    get:
      summary: Get V3 Runs Route Route Route Type Route Type
      description: View all trip/service runs for a specific route id and route type.
      operationId: Runs_ForRouteAndRouteType
      x-api-path-slug: v3runsrouteroute-idroute-typeroute-type-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: route_id
        description: Identifier of route; values returned by Routes API - v3/routes
      - in: path
        name: route_type
        description: Number identifying transport mode; values returned via RouteTypes
          API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Runs
      - Route
      - Route
      - Id
      - Route
      - Type
      - Route
      - Type
  /v3/runs/{run_id}:
    get:
      summary: Get V3 Runs Run
      description: View all trip/service runs for a specific run id.
      operationId: Runs_ForRun
      x-api-path-slug: v3runsrun-id-get
      parameters:
      - in: query
        name: devid
        description: Your developer id
      - in: path
        name: run_id
        description: Identifier of a trip/service run; values returned by Runs API
          - /v3/route/{route_id} and Departures API
      - in: query
        name: signature
        description: Authentication signature for request
      - in: query
        name: token
        description: Please ignore
      responses:
        200:
          description: OK
      tags:
      - Runs
      - Run
      - Id
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---