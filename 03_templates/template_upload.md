# Create & Upload Vital Signs Template

## Template creation
Created a Vital Signs template in Archetype Designer by selecting:
- openEHR-EHR-OBSERVATION.pulse.v2
- openEHR-EHR-OBSERVATION.blood_pressure.v2

Downloaded the template as an OPT file.

## Upload to EHRbase
Uploaded the OPT using the Template API endpoint:
POST /ehrbase/rest/openehr/v1/definition/template/adl1.4

## Result
Template registered successfully and available for composition posting.
