# Experimental Design

## Study Title

Geographic Generalization as a First-Class Problem in Climate GeoAI: A Cross-City Benchmark and Failure-Decomposition Framework for Urban Heat

## Climate Regimes

### Arid Cities

* Phoenix, Arizona
* Tucson, Arizona
* Las Vegas, Nevada

### Humid Cities

* Atlanta, Georgia
* Houston, Texas
* Miami, Florida

## Justification

The six-city design creates a controlled climate-regime contrast between arid and humid environments. Urban heat processes, vegetation-water relationships, impervious surface effects, and cooling mechanisms differ substantially between desert and humid subtropical climates. This allows geographic generalization to be evaluated under both same-climate and cross-climate transfer settings.

## Spatial Unit

Primary unit: Census tract

Alternative unit: Census block group (if required)

## Temporal Window

* Years: 2020–2024
* Season: June–August
* Time period: Daytime
* Aggregation: Median

## Target Variables

### Physical Exposure

Land Surface Temperature (LST)

### Vulnerability

Heat Vulnerability Index (HVI)

## Transfer Experiments

### A. Within-City

* Phoenix → Phoenix
* Tucson → Tucson
* Las Vegas → Las Vegas
* Atlanta → Atlanta
* Houston → Houston
* Miami → Miami

### B. Same-Climate Transfer

* Phoenix → Tucson
* Phoenix → Las Vegas

### C. Cross-Climate Transfer

* Phoenix → Atlanta
* Phoenix → Houston
* Phoenix → Miami

## Validation Strategy

* Leave-one-city-out transfer evaluation
* Spatial block cross-validation within cities
* Random train/test splits are prohibited because they inflate performance estimates due to spatial autocorrelation
