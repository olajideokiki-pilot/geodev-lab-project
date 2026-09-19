# Data Notes

## GRID3 Nigeria Operational State Boundaries

- **Source:** https://data.grid3.org/datasets/c41532b720504f4799fe20438b7e3b7f_0/explore?location=9.077959%2C8.685290%2C6
- **Date downloaded:** 08/09/2026
- **Columns:** globalid (text), uniq_id (numbers), timestamp (date), editor (text), statename (text), statecode (text), capacity (text), source (text), capacity (text)
- **Nulls:** No
- **Features:** 37
- **Geometry type:** Polygon (Multipolygon)
- **Coverage notes:** Covers properly

## GRID3 NGA Operational LGA Boundaries (Lagos State)

- **Source:** https://data.grid3.org/datasets/2bb616a49ee84f409427cc2143787113_0/explore?location=9.077959%2C8.685290%2C6
- **Date downloaded:** 08/09/2026
- **Columns:** globalid (text), uniq_id (numbers), timestamp (date), editor (text), lganame (text), lgacode (text), statename (text), statecode (text), source (text), amapcode (text)
- **Nulls:** No
- **Features:** 20
- **Geometry type:** Polygon (Multipolygon)
- **Coverage notes:** Covers properly

## GRID3 NGA Operational Wards (Ikeja)

- **Source:** https://data.grid3.org/datasets/0824aded5f5a4d39b10871c667aa8ccf_0/explore?location=6.605815%2C3.392352%2C12
- **File:** GRA
- **Date downloaded:** 08/09/2026
- **Columns:** globalid (text), uniq_id (numbers), timestamp (date), editor (text), wardname (text), wardcode (text), lganame (text), lgacode (text), statename (text), statecode (text), amapcode (text), status (text), source (text), Urban (text)
- **Nulls found:** Nil
- **Features:** 18
- **Geometry type:** Polygon (Multipolygon)
- **Coverage notes:** Covers properly

## OpenStreetMap Roads

- **Source:** OpenStreetMap, pulled via QuickOSM
- **Date extracted:** 11/09/2026
- **Query:** `highway=*` within Ikeja LGA
- **Columns:** full_id (text), osm_id (text), osm_type (text), sidewalk_r (text), footway (text), bus (text), train (text), highway (text), alt_name (text), admin_leve (text), source_dat (text), full_name_ (text), public_tra (text), name_en (text), name_zh (text), public_tra (text), official_n (text), passenger_ (text), is_in (text), passenger_
- **Features:** 1,276
- **Coverage notes:** Looks good and complete in the area



## All source layers were delivered in EPSG:32631 (WGS 84 / UTM Zone 31N).

- **Study area**: Ikeja LGA, extracted from the GRID3 LGA dataset.
- All layers were clipped to the study area boundary and then reprojected to EPSG:32631 (UTM 31N).
- **Area check**: post-reprojection, Ikeja LGA measures 40.82 km², against a cited reference figure of approximately 42.31 km².
- Working files are stored in `data/processed/`; raw source files remain untouched.
